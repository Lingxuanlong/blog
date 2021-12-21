---
title: 文件上传应用
date: 2016-12-15
tags:
 - tag3
categories: 
 - IO操作

---

####    1.1.1  输入输出流

####    1.2.1 文件上传 文件批量上传/下载 

#####     文件上传

```java
/*
    *  文件上传
    */
    @RequestMapping(value = "/upload",method = RequestMethod.POST)
    public CposResult Upload(HttpServletRequest request, HttpServletResponse response){

        CposResult cposResult = new CposResult();

        //获取请求体的Requst的文件流
        MultipartHttpServletRequest fileMap = (MultipartHttpServletRequest) request;


        if(!fileMap.equals(null)){
            Map<String, MultipartFile> forMap = fileMap.getFileMap();

            for (Map.Entry<String, MultipartFile> multipartFile : forMap.entrySet()) {
                MultipartFile file = multipartFile.getValue();
                //传入文件名
                String filename = file.getName();
                //获取文件的后缀名
                String extFileName = file.getOriginalFilename().toString().split("\\.")[1];

                //创建新文件名称
                String newName = System.currentTimeMillis()+"."+extFileName;

                //上传文件地址
                String upUrl = UploadPath+"//"+newName;

                File newFile = new File(upUrl);
                //判断文件夹是否存在
                if(!newFile.exists()){
                    newFile.mkdir();
                }

                try {
                    file.transferTo(newFile);
                } catch (IOException e) {
                    e.printStackTrace();
                    cposResult.setMsg("文件上传失败");
                    cposResult.setCode(500);
                    return cposResult;
                }
                cposResult.setData(upUrl);
            }
        }


        return cposResult;
    }
```

#####   下载

####    1.2.2  文件上传/下载 到FTP服务器

​    

```tex
 实现思路：首先需要创建一个FtpConfig的配置类  然后在FileUtil 里面编写连接Ftp以及下载/上传 ftp图片的接口 
```

​    

####    1.2.3   文件上传/下载 到FastDFS

####    1.2.4  文件上传/下载 到七牛云

配置七牛云秘钥

```
#千牛云 文件配置
qnos:
    access_key: i6AzZs1eIHKYPqpERENt4LdHe2NCJw-LHXpFND3J
    secret_key: 4vccePk3qZD9gg2HuHuydzQZDw4cFEfB2gGPkksx
    backet_name: cpos-files
```

```java
    //获取请求体的Requst的文件流
        MultipartHttpServletRequest fileMap = (MultipartHttpServletRequest) request;

        Config.ACCESS_KEY = accessKey;
        Config.SECRET_KEY = secretKey;
        Config.UP_HOST = "http://up-z2.qiniup.com";
        Mac mac = new Mac(Config.ACCESS_KEY, Config.SECRET_KEY);
        // 请确保该bucket已经存在
        String bucketName = backetName;
        PutPolicy putPolicy = new PutPolicy(bucketName);
        String uptoken = null;


        if(!fileMap.equals(null)){
            Map<String, MultipartFile> forMap = fileMap.getFileMap();

            for (Map.Entry<String, MultipartFile> multipartFile : forMap.entrySet()) {
                MultipartFile file = multipartFile.getValue();
                //传入文件名
                String filename = file.getName();
                //获取文件的后缀名
                String extFileName = file.getOriginalFilename().toString().split("\\.")[1];

                //创建新文件名称
                String key = System.currentTimeMillis()+"."+extFileName;

                //上传文件地址
                String localFile = UploadPath+"//"+key;

                File newFile = new File(localFile);
                //判断文件夹是否存在
                if(!newFile.exists()){
                    newFile.mkdir();
                }

                try {
                    file.transferTo(newFile);

                    try {
                        uptoken = putPolicy.token(mac);
                    } catch (AuthException e) {
                        e.printStackTrace();
                    } catch (JSONException e) {
                        e.printStackTrace();
                    }
                    PutExtra extra = new PutExtra();
                    PutRet ret = IoApi.putFile(uptoken, key, localFile, extra);
                    // http://qkg9ehwva.hn-bkt.clouddn.com
                    cposResult.setData(ret);
                } catch (IOException e) {
                    e.printStackTrace();
                }

            }
        }
```