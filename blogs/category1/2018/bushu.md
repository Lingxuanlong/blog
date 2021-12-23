# 编程环境和软件设施安装手册

#### 编程环境和软件设施安装手册

#### 环境声明（重要！！！）

**安装配置Linux系统环境**

```
MacOS系统图文教程（点击可查看）
MacOS系统视频教程（点击可查看）
Windows系统图文教程（点击可查看）
```
**Git工具安装**

```
方式一：通过包管理器安装
方法二：通过源码编译安装
```
**JDK（Java环境）安装**

```
准备JDK安装包
卸载已有的OpenJDK（如果有）
创建目录并解压
配置JDK环境变量
验证JDK安装结果
```
**Node环境安装**

```
准备Node安装包
创建目录并解压
配置Node系统环境变量
检查安装结果
```
**Python环境安装**

```
准备python3安装包并解压
安装相关预备环境
编译并安装
添加软链接
验证安装
```
**Maven项目构建和管理工具安装**

```
准备Maven安装包并解压
配置Maven加速镜像源
配置环境变量
检验安装结果
```
**MySQL数据库部署和安装**

```
首先准备安装包
卸载系统自带的Mariadb（如果有）
解压MySQL安装包
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
创建mysql用户和用户组
修改mysql目录的归属用户
准备MySQL的配置文件
正式开始安装MySQL
复制启动脚本到资源目录
设置MySQL系统服务并开启自启
启动mysqld
将mysql的bin目录加入PATH环境变量
首次登陆MySQL
接下来修改root账户密码
设置远程主机登录
最后利用Navicat等工具进行测试即可：
```
**Redis缓存安装部署**

```
首先准备Redis安装包
解压安装包
编译并安装
将Redis安装为系统服务并后台启动
查看Redis服务启动情况
启动Redis客户端并测试
设置允许远程连接
设置访问密码
```
**消息队列RabbitMQ安装部署**

```
首先安装erlang环境
安装RabbitMQ
设置RabbitMQ开机启动
启动RabbitMQ服务
开启web可视化管理插件：
访问可视化管理界面：
```
**应用服务器Tomcat安装部署**

```
准备安装包
解压并安装
启动Tomcat
配置快捷操作和开机启动
```
**Web服务器Nginx安装部署**

```
首先安装包并解压
预先安装额外的依赖
编译安装nginx
启动Nginx
浏览器验证启动情况
```
**Docker环境安装**

```
安装Docker
开启Docker服务
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 查看安装结果

#### 设置开机启动

```
配置Docker镜像下载加速
```
**Kubernetes集群部署**

```
概 述
节点规划
准备工作
组件安装
0x01. Docker安装（所有节点）
0x02. kubelet、kubeadm、kubectl安装（所有节点）
Master节点配置
0x01. 初始化 k8s集群
0x02. 配置 kubectl
0x03. 安装Pod网络
添加 Slave节点
效果验证
拆卸集群
安装 dashboard
```
**ElasticSearch集群部署**

```
环境准备
Elasticsearch 集群配置
集群启动前准备
启动 Elasticsearch集群
安装IK分词器
```
**ZooKeeper安装部署**

```
准备安装包
解压并安装
创建data目录
创建配置文件并修改
启动ZooKeeper
配置环境变量
设置开机自启
```
**消息队列Kafka安装部署**

```
首先准备ZooKeeper服务
准备Kafka安装包
解压并安装
创建logs目录
修改配置文件
启动Kafka
实验验证
```
**注意事项**

**持续更新中...**

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# 环境声明（重要！！！）

```
本文档所有实验、环境、工具、软件均基于CentOS 7.4 64bit Linux操作系统进行
本文档所使用的 Linux系统ISO镜像 、 软件安装包 都已经提前下载并备好，需要的童鞋可以直接
扫描下方二维码关注，然后回复 “ 软件包 ” 三个字即可自行领取：
```
```
本文档在 Github开源项目：github.com/hansonwang99/JavaCollection 中已收录，有详细
自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
#### 另外， 联系作者、提意⻅，可以参看本文档尾部，有相应联系方式。

接下来，我们就从Linux操作系统环境的安装开始。

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# 安装配置LINUX系统环境

#### 关于这一部分内容，之前已经出过「视频教程」和「图文教程」，可直接点击查看：

## MACOS系统图文教程（点击可查看）

## MACOS系统视频教程（点击可查看）

## WINDOWS系统图文教程（点击可查看）

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# GIT工具安装

## 方式一：通过包管理器安装

在Linux上安装Git向来 **仅需一行命令** 即可搞定，因为各式各样的 **包管理器** 帮了我们大忙，所以对于

```
CentOS系统来讲，直接执行如下命令即可安装：
```
当然通过这种方式安装的Git可能不是较新版的Git，以我们的实验环境CentOS 7.4来说，这种方

式安装的Git版本为1.8.3.1，不过一般来说是够用的。

## 方法二：通过源码编译安装

如果想安装较新版本的Git，则需要自行下载Git源码来编译安装。

**1 、准备Git安装包**

我这里选择安装的是2.26.2版，将下载好的安装包v2.26.2.tar.gz直接放在了root目录下

然后将其本地解压，得到git-2.26.2目录：

#### 2 、提前安装可能所需的依赖

**3 、编译安装Git**

#### 进入到对应目录，执行配置、编译、安装命令即可，如下所示：

```
yum install git
```
```
[root@localhost ~]# tar -zxvf v2.26.2.tar.gz
```
```
yum install curl-devel expat-devel gettext-devel openssl-devel zlib-
devel gcc-c++ perl-ExtUtils-MakeMaker
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

**4 、将Git加入环境变量**

将Git的可执行程序加入环境变量，便于后续使用

#### 编辑配置文件：

尾部加入Git的bin路径配置即可

最后执行 source /etc/profile使环境变量生效即可。

#### 5 、查看安装结果

执行git --version查看安装后的版本即可

```
[root@localhost ~]# cd git-2.26.2/
[root@localhost git-2.26.2]# make configure
[root@localhost git-2.26.2]# ./configure --prefix=/usr/local/git
[root@localhost git-2.26.2]# make profix=/usr/local/git
[root@localhost git-2.26.2]# make install
```
```
vim /etc/profile
```
```
export GIT_HOME=/usr/local/git
export PATH=$PATH:$GIT_HOME/bin
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# JDK（JAVA环境）安装

```
注意：这里安装的是Oracle JDK
```
## 准备JDK安装包

我这里下载的是jdk-8u161-linux-x64.tar.gz安装包，并将其直接放在了root目录下

## 卸载已有的OPENJDK（如果有）

如果系统自带有OpenJDK，可以按照如下步骤提前卸载之。

首先查找已经安装的OpenJDK包：

接下来可以将java开头的安装包均卸载即可：

```
rpm -qa | grep java
```
```
yum -y remove java-1.7.0-openjdk-1.7.0.141-2.6.10.5.el7.x86_
yum -y remove java-1.8.0-openjdk-1.8.0.131-11.b12.el7.x86_
```
#### ... 省略 ...

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 创建目录并解压

1 、在/usr/local/下创建java文件夹并进入

2 、将上面准备好的JDK安装包解压到/usr/local/java中即可

解压完之后，/usr/local/java目录中会出现一个jdk1.8.0_161的目录

## 配置JDK环境变量

编辑/etc/profile文件，在文件尾部加入如下JDK环境配置即可

#### 然后执行如下命令让环境变量生效

## 验证JDK安装结果

#### 输入如下命令即可检查安装结果：

```
cd /usr/local/
mkdir java
cd java
```
```
tar -zxvf /root/jdk-8u161-linux-x64.tar.gz -C ./
```
```
JAVA_HOME=/usr/local/java/jdk1.8.0_
CLASSPATH=$JAVA_HOME/lib/
PATH=$PATH:$JAVA_HOME/bin
export PATH JAVA_HOME CLASSPATH
```
```
source /etc/profile
```
```
java -version
```
```
javac
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# NODE环境安装

## 准备NODE安装包

我这里下载的是node-v12.16.3-linux-x64.tar.xz安装包，并将其直接放在了root目录下

## 创建目录并解压

1 、在/usr/local/下创建node文件夹并进入

2 、将Node的安装包解压到/usr/local/node中即可

解压完之后，/usr/local/node目录中会出现一个node-v12.16.3-linux-x64的目录

## 配置NODE系统环境变量

编辑~/.bash_profile文件，在文件末尾追加如下信息:

```
cd /usr/local/
mkdir node
cd node
```
```
[root@localhost node]# tar -xJvf /root/node-v12.16.3-linux-x64.tar.xz -
C ./
```
```
# Nodejs
export PATH=/usr/local/node/node-v12.16.3-linux-x64/bin:$PATH
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 刷新环境变量，使之生效即可：

## 检查安装结果

#### 均有版本信息输出即可：

```
source ~/.bash_profile
```
```
node -v
```
```
npm version
```
```
npx -v
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# PYTHON环境安装

```
CentOS 7.4默认自带了一个Python2.7环境：
```
然而现在主流都是Python3，所以接下来再装一个Python3，打造一个共存的环境。

## 准备PYTHON3安装包并解压

我这里下载的是Python-3.8.3.tgz安装包，并将其直接放在了/root目录下

#### 执行如下命令解压之：

则可以在当前目录得到文件夹：Python-3.8.

## 安装相关预备环境

#### 直接执行如下命令即可：

## 编译并安装

这里指定了安装目录为/usr/local/python3，有需要可以自定义

```
tar zxvf Python-3.8.3.tgz
```
```
yum install zlib-devel bzip2-devel openssl-devel ncurses-devel sqlite-
devel readline-devel tk-devel gcc make
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

等安装过程完毕，/usr/local/python3目录就会生成了

## 添加软链接

我们还需要将刚刚安装生成的目录/usr/local/python3里的python3可执行文件做一份软链接，链

接到/usr/bin下，方便后续使用python

## 验证安装

命令行输入python3，即可查看Python3版本的安装结果

而输入python，依然还是python2.7.5环境

```
cd Python-3.8.3/
./configure prefix=/usr/local/python
make && make install
```
```
ln -s /usr/local/python3/bin/python3 /usr/bin/python
ln -s /usr/local/python3/bin/pip3 /usr/bin/pip
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# MAVEN项目构建和管理工具安装

## 准备MAVEN安装包并解压

这里下载的是apache-maven-3.6.3-bin.tar.gz安装包，并将其放置于提前创建好的/opt/maven

目录下。

#### 执行命令解压之：

即可在当前目录得到/opt/maven/apache-maven-3.6.3目录

## 配置MAVEN加速镜像源

这里配置的是阿里云的maven镜像源。

编辑修改 /opt/maven/apache-maven-3.6.3/conf/settings.xml

文件，在<mirrors></mirrors>标签对里添加如下内容即可：

```
tar zxvf apache-maven-3.6.3-bin.tar.gz
```
```
<mirror>
<id>alimaven</id>
<name>aliyun maven</name>
<url>http://maven.aliyun.com/nexus/content/groups/public/</url>
<mirrorOf>central</mirrorOf>
</mirror>
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 配置环境变量

#### 因为下载的是二进制版安装包，所以解压完，配置好环境变量即可使用了。

编辑修改/etc/profile文件，在文件尾部添加如下内容，配置maven的安装路径

接下来执行source /etc/profile来刷新环境变量，让maven环境的路径配置生效，

## 检验安装结果

执行mvn –v，能打印出maven版本信息说明安装、配置成功：

```
export MAVEN_HOME=/opt/maven/apache-maven-3.6.
export PATH=$MAVEN_HOME/bin:$PATH
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# MYSQL数据库部署和安装

## 首先准备安装包

这里下载的是mysql-5.7.30-linux-glibc2.12-x86_64.tar.gz安装包，并将其直接放在了root

目录下

## 卸载系统自带的MARIADB（如果有）

如果系统之前自带Mariadb，可以先卸载之。

首先查询已安装的Mariadb安装包：

#### 将其均卸载之：

## 解压MYSQL安装包

将上面准备好的MySQL安装包解压到/usr/local/目录，并重命名为mysql

```
rpm -qa|grep mariadb
```
```
yum -y remove mariadb-server-5.5.56-2.el7.x86_
yum -y remove mariadb-5.5.56-2.el7.x86_
yum -y remove mariadb-devel-5.5.56-2.el7.x86_
yum -y remove mariadb-libs-5.5.56-2.el7.x86_
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 创建MYSQL用户和用户组

同时新建/usr/local/mysql/data目录，后续备用

## 修改MYSQL目录的归属用户

[root@localhost mysql]# chown -R mysql:mysql ./

## 准备MYSQL的配置文件

在/etc目录下新建my.cnf文件

#### 写入如下简化配置：

```
tar -zxvf /root/mysql-5.7.30-linux-glibc2.12-x86_64.tar.gz -C
/usr/local/
mv mysql-5.7.30-linux-glibc2.12-x86_64 mysql
```
```
groupadd mysql
useradd -g mysql mysql
```
```
[mysql]
# 设置mysql客户端默认字符集
default-character-set=utf8
socket=/var/lib/mysql/mysql.sock
```
```
[mysqld]
skip-name-resolve
#设置 3306 端口
port = 3306
socket=/var/lib/mysql/mysql.sock
# 设置mysql的安装目录
basedir=/usr/local/mysql
# 设置mysql数据库的数据的存放目录
datadir=/usr/local/mysql/data
# 允许最大连接数
max_connections= 200
# 服务端使用的字符集默认为 8 比特编码的latin1字符集
character-set-server=utf8
# 创建新表时将使用的默认存储引擎
default-storage-engine=INNODB
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

同时使用如下命令创建/var/lib/mysql目录，并修改权限：

## 正式开始安装MYSQL

#### 执行如下命令正式开始安装：

```
注意：记住上面打印出来的root的密码，后面首次登陆需要使用
```
## 复制启动脚本到资源目录

#### 执行如下命令复制：

并修改/etc/init.d/mysqld，修改其basedir和datadir为实际对应目录：

```
lower_case_table_names= 1
max_allowed_packet=16M
```
```
mkdir /var/lib/mysql
chmod 777 /var/lib/mysql
```
```
cd /usr/local/mysql
./bin/mysqld --initialize --user=mysql --basedir=/usr/local/mysql --
datadir=/usr/local/mysql/data
```
```
[root@localhost mysql]# cp ./support-files/mysql.server
/etc/init.d/mysqld
```
```
basedir=/usr/local/mysql
datadir=/usr/local/mysql/data
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 设置MYSQL系统服务并开启自启

首先增加mysqld服务控制脚本执行权限：

同时将mysqld服务加入到系统服务：

最后检查mysqld服务是否已经生效即可：

这样就表明mysqld服务已经生效了，在 2 、 3 、 4 、 5 运行级别随系统启动而自动启动，以后可以直接使

用service命令控制mysql的启停。

## 启动MYSQLD

#### 直接执行：

```
chmod +x /etc/init.d/mysqld
```
```
chkconfig --add mysqld
```
```
chkconfig --list mysqld
```
```
service mysqld start
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 将 MYSQL 的 BIN 目录加入 PATH 环境变量

这样方便以后在任意目录上都可以使用mysql提供的命令。

编辑 ~/.bash_profile文件，在文件末尾处追加如下信息:

#### 最后执行如下命令使环境变量生效

```
export PATH=$PATH:/usr/local/mysql/bin
```
```
source ~/.bash_profile
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 首次登陆MYSQL

以root账户登录mysql，使用上文安装完成提示的密码进行登入

## 接下来修改ROOT账户密码

在mysql的命令行执行如下命令即可，密码可以换成你想用的密码即可：

```
mysql -u root -p
```
```
mysql>alter user user() identified by "111111";
mysql>flush privileges;
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 比如这里将密码设置成简单的“111111”了。

## 设置远程主机登录

## 最后利用NAVICAT等工具进行测试即可：

```
mysql> use mysql;
mysql> update user set user.Host='%' where user.User='root';
mysql> flush privileges;
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# REDIS缓存安装部署

## 首先准备REDIS安装包

这里下载的是redis-5.0.8.tar.gz安装包，并将其直接放在了root目录下

## 解压安装包

1 、在/usr/local/下创建redis文件夹并进入

2 、将Redis安装包解压到/usr/local/redis中即可

解压完之后，/usr/local/redis目录中会出现一个redis-5.0.8的目录

## 编译并安装

## 将 REDIS 安装为系统服务并后台启动

进入utils目录，并执行如下脚本即可：

#### 此处我全部选择的默认配置即可，有需要可以按需定制

```
cd /usr/local/
mkdir redis
cd redis
```
```
[root@localhost redis]# tar zxvf /root/redis-5.0.8.tar.gz -C ./
```
```
cd redis-5.0.8/
make && make install
```
```
[root@localhost redis-5.0.8]# cd utils/
[root@localhost utils]# ./install_server.sh
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 查看REDIS服务启动情况

直接执行如下命令来查看Redis的启动结果：

## 启动REDIS客户端并测试

```
systemctl status redis_6379.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

启动自带的redis-cli客户端，测试通过：

#### 但是此时只能在本地访问，无法远程连接，因此还需要做部分设置

## 设置允许远程连接

编辑redis配置文件

将 bind 127.0.0.1 修改为 0.0.0.0

然后重启Redis服务即可：

## 设置访问密码

编辑redis配置文件

```
vim /etc/redis/6379.conf
```
```
systemctl restart redis_6379.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 找到如下内容：

去掉注释，将foobared修改为自己想要的密码，保存即可。

保存，重启Redis服务即可

#### 这样后续的访问需要先输入密码认证通过方可：

```
vim /etc/redis/6379.conf
```
```
#requirepass foobared
```
```
requirepass codesheep
```
```
systemctl restart redis_6379.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# 消息队列RABBITMQ安装部署

## 首先安装ERLANG环境

因为RabbitMQ需要erlang环境的支持，所以必须先安装erlang。

我们这里要安装的是 erlang-22.3.3-1.el7.x86_64.rpm，所以首先执行如下命令来安装其对应的

```
yum repo：
```
接下来执行如下命令正式安装erlang环境：

```
curl -s
https://packagecloud.io/install/repositories/rabbitmq/erlang/script.rpm
.sh | sudo bash
```
```
yum install erlang-22.3.3-1.el7.x86_64
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 接着上面提示再次执行如下命令即可：

接下来可以直接执行如下命令，测试erlang是否安装成功：

```
yum load-transaction /tmp/yum_save_tx.2020-05-14.22-21.n0cwzm.yumtx
```
```
erl
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 安装RABBITMQ

接下来正式开始安装rabbitmq，首先依然是安装其对应的yum repo：

然后执行如下命令正式安装rabbitmq：

```
curl -s https://packagecloud.io/install/repositories/rabbitmq/rabbitmq-
server/script.rpm.sh | sudo bash
```
```
yum install rabbitmq-server-3.8.3-1.el7.noarch
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 设置RABBITMQ开机启动

## 启动RABBITMQ服务

## 开启WEB可视化管理插件：

## 访问可视化管理界面：

#### 浏览器输入：你的服务器IP:15672

#### 能看到网⻚登录入口即可。

```
chkconfig rabbitmq-server on
```
```
systemctl start rabbitmq-server.service
```
```
rabbitmq-plugins enable rabbitmq_management
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 我们可以在后台先添加一个用户/密码对：

#### 然后登录网⻚即可：

```
rabbitmqctl add_user codesheep 123456
rabbitmqctl set_user_tags codesheep administrator
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# 应用服务器TOMCAT安装部署

## 准备安装包

这里使用的是8.5.55版：apache-tomcat-8.5.55.tar.gz，直接将其放在了/root目录下

## 解压并安装

在/usr/local/下创建tomcat文件夹并进入

2 、将Tomcat安装包解压到/usr/local/tomcat中即可

解压完之后，/usr/local/tomcat目录中会出现一个apache-tomcat-8.5.55的目录

## 启动TOMCAT

直接进apache-tomcat-8.5.55目录，执行其中bin目录下的启动脚本即可

```
cd /usr/local/
mkdir tomcat
cd tomcat
```
```
[root@localhost tomcat]# tar -zxvf /root/apache-tomcat-8.5.55.tar.gz -C
./
```
```
[root@localhost apache-tomcat-8.5.55]# cd bin/
[root@localhost bin]# ./startup.sh
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 这时候浏览器访问：你的主机IP:8080，得到如下画面说明成功启动了

## 配置快捷操作和开机启动

首先进入/etc/rc.d/init.d目录，创建一个名为tomcat的文件，并赋予执行权限

接下来编辑tomcat文件，并在其中加入如下内容：

```
[root@localhost ~]# cd /etc/rc.d/init.d/
[root@localhost init.d]# touch tomcat
[root@localhost init.d]# chmod +x tomcat
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

这样后续对于Tomcat的开启和关闭只需要执行如下命令即可：

#### 最后加入开机启动即可：

```
#!/bin/bash
#chkconfig:- 20 90
#description:tomcat
#processname:tomcat
TOMCAT_HOME=/usr/local/tomcat/apache-tomcat-8.5.55
case $1 in
start) su root $TOMCAT_HOME/bin/startup.sh;;
stop) su root $TOMCAT_HOME/bin/shutdown.sh;;
*) echo "require start|stop" ;;
```
```
esac
```
```
service tomcat start
service tomcat stop
```
```
chkconfig --add tomcat
chkconfig tomcat on
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# WEB服务器NGINX安装部署

## 首先安装包并解压

这里下载的是nginx-1.17.10.tar.gz安装包，并将其直接放在了root目录下

1 、在/usr/local/下创建nginx文件夹并进入

2 、将Nginx安装包解压到/usr/local/nginx中即可

解压完之后，/usr/local/nginx目录中会出现一个nginx-1.17.10的目录

## 预先安装额外的依赖

## 编译安装NGINX

安装完成后，Nginx的可执行文件位置位于

```
cd /usr/local/
mkdir nginx
cd nginx
```
```
[root@localhost nginx]# tar zxvf /root/nginx-1.17.10.tar.gz -C ./
```
```
yum -y install pcre-devel
yum -y install openssl openssl-devel
```
```
cd nginx-1.17.10
./configure
make && make install
```
```
/usr/local/nginx/sbin/nginx
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 启动NGINX

#### 直接执行如下命令即可：

如果想停止Nginx服务，可执行：

如果修改了配置文件后想重新加载Nginx，可执行：

#### 注意其配置文件位于：

## 浏览器验证启动情况

```
[root@localhost sbin]# /usr/local/nginx/sbin/nginx
```
```
/usr/local/nginx/sbin/nginx -s stop
```
```
/usr/local/nginx/sbin/nginx -s reload
```
```
/usr/local/nginx/conf/nginx.conf
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# DOCKER环境安装

## 安装DOCKER

#### 静候安装完毕即可

## 开启DOCKER服务

```
yum install -y docker
```
```
systemctl start docker.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 查看安装结果

## 设置开机启动

## 配置DOCKER镜像下载加速

默认安装后的Docker环境在拉取Docker镜像时速度很慢：

```
docker version
```
```
systemctl enable docker.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

因此我们需要手动配置镜像加速源，提升获取Docker镜像的速度。

#### 配置方法非常简单。

#### 直接编辑配置文件：

#### 在其中加入加速镜像源地址即可：

比如这里使用的是网易的加速源，其他像阿里云、DaoCloud这些也都提供加速源，按需选择即可。

加完加速地址后，重新加载配置文件，重启docker服务即可：

这样镜像加速器就配置完成了，后续下载docker镜像速度将大增。

```
vim /etc/docker/daemon.json
```
#### {

```
"registry-mirrors": ["http://hub-mirror.c.163.com"]
}
```
```
systemctl daemon-reload
systemctl restart docker.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 主机名 IP ⻆色

```
k8s-master 192.168.39.79 k8s主节点
```
```
k8s-node-1 192.168.39.77 k8s从节点
```
```
k8s-node-2 192.168.39.78 k8s从节点
```
# KUBERNETES集群部署

## 概 述

Kubernetes集群的搭建方法其实有多种，比如我在之前的文章《利用K8S技术栈打造个人私有云（连载

之：K8S集群搭建）》中使用的就是二进制的安装方法。虽然这种方法有利于我们理解 k8s集群，但却过

于繁琐。而 kubeadm是 Kubernetes官方提供的用于快速部署Kubernetes集群的工具，其历经发展如

今已经比较成熟了，利用其来部署 Kubernetes集群可以说是非常好上手，操作起来也简便了许多，下

面详细叙述之。

## 节点规划

本文准备部署一个 **一主两从** 的 **三节点** Kubernetes集群，整体节点规划如下表所示：

#### 下面介绍一下各个节点的软件版本：

```
操作系统：CentOS-7.4-64Bit
Docker版本：1.13.1
Kubernetes版本：1.13.1
```
所有节点都需要安装以下组件：

```
Docker：不用多说了吧
kubelet：运行于所有 Node上，负责启动容器和 Pod
kubeadm：负责初始化集群
kubectl： k8s命令行工具，通过其可以部署/管理应用 以及CRUD各种资源
```
## 准备工作

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 所有节点关闭防火墙

#### 禁用SELINUX

```
所有节点关闭 swap
```
#### 设置所有节点主机名

```
所有节点 主机名/IP加入 hosts解析
```
编辑 /etc/hosts文件，加入以下内容：

## 组件安装

### 0x01. Docker安装（所有节点）

```
不赘述了，参考上文Docker环境安装
```
### 0x02. kubelet、kubeadm、kubectl安装（所有节点）

```
首先准备repo
```
```
systemctl disable firewalld.service
systemctl stop firewalld.service
```
```
setenforce 0
```
```
vi /etc/selinux/config
SELINUX=disabled
```
```
swapoff -a
```
```
hostnamectl --static set-hostname k8s-master
hostnamectl --static set-hostname k8s-node-1
hostnamectl --static set-hostname k8s-node-2
```
```
192 .168.39.79 k8s-master
192 .168.39.77 k8s-node-1
192 .168.39.78 k8s-node-2
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 然后执行如下指令来进行安装

## MASTER节点配置

### 0x01. 初始化 k8s集群

为了应对网络不畅通的问题，我们国内网络环境只能提前手动下载相关镜像并重新打 tag :

```
cat>>/etc/yum.repos.d/kubrenetes.repo<<EOF
[kubernetes]
name=Kubernetes Repo
baseurl=https://mirrors.aliyun.com/kubernetes/yum/repos/kubernetes-el7-
x86_64/
gpgcheck= 0
gpgkey=https://mirrors.aliyun.com/kubernetes/yum/doc/yum-key.gpg
EOF
```
```
setenforce 0
sed -i 's/^SELINUX=enforcing$/SELINUX= disabled/' /etc/selinux/config
```
```
yum install -y kubelet kubeadm kubectl
systemctl enable kubelet && systemctl start kubelet
```
```
docker pull mirrorgooglecontainers/kube-apiserver:v1.13.1
docker pull mirrorgooglecontainers/kube-controller-manager:v1.13.1
docker pull mirrorgooglecontainers/kube-scheduler:v1.13.1
docker pull mirrorgooglecontainers/kube-proxy:v1.13.1
docker pull mirrorgooglecontainers/pause:3.1
docker pull mirrorgooglecontainers/etcd:3.2.24
docker pull coredns/coredns:1.2.6
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

然后再在 Master节点上执行如下命令初始化 k8s集群：

```
--kubernetes-version: 用于指定 k8s版本
--apiserver-advertise-address：用于指定使用 Master的哪个network interface进行通
信，若不指定，则 kubeadm会自动选择具有默认网关的 interface
--pod-network-cidr：用于指定Pod的网络范围。该参数使用依赖于使用的网络方案，本文
将使用经典的flannel网络方案。
```
执行命令后，控制台给出了如下所示的详细集群初始化过程：

```
docker pull registry.cn-shenzhen.aliyuncs.com/cp_m/flannel:v0.10.0-
amd64
```
```
docker tag mirrorgooglecontainers/kube-apiserver:v1.13.1
k8s.gcr.io/kube-apiserver:v1.13.1
docker tag mirrorgooglecontainers/kube-controller-manager:v1.13.1
k8s.gcr.io/kube-controller-manager:v1.13.1
docker tag mirrorgooglecontainers/kube-scheduler:v1.13.1
k8s.gcr.io/kube-scheduler:v1.13.1
docker tag mirrorgooglecontainers/kube-proxy:v1.13.1 k8s.gcr.io/kube-
proxy:v1.13.1
docker tag mirrorgooglecontainers/pause:3.1 k8s.gcr.io/pause:3.1
docker tag mirrorgooglecontainers/etcd:3.2.24 k8s.gcr.io/etcd:3.2.24
docker tag coredns/coredns:1.2.6 k8s.gcr.io/coredns:1.2.6
docker tag registry.cn-shenzhen.aliyuncs.com/cp_m/flannel:v0.10.0-amd64
quay.io/coreos/flannel:v0.10.0-amd64
```
```
docker rmi mirrorgooglecontainers/kube-apiserver:v1.13.1
docker rmi mirrorgooglecontainers/kube-controller-manager:v1.13.1
docker rmi mirrorgooglecontainers/kube-scheduler:v1.13.1
docker rmi mirrorgooglecontainers/kube-proxy:v1.13.1
docker rmi mirrorgooglecontainers/pause:3.1
docker rmi mirrorgooglecontainers/etcd:3.2.24
docker rmi coredns/coredns:1.2.6
docker rmi registry.cn-shenzhen.aliyuncs.com/cp_m/flannel:v0.10.0-amd64
```
```
kubeadm init --kubernetes-version=v1.13.1 --apiserver-advertise-address
192 .168.39.79 --pod-network-cidr= 10 .244.0.0/16
```
```
[root@localhost ~]# kubeadm init --config kubeadm-config.yaml
W1224 11 :01:25.408209 10137 strict.go:54] error unmarshaling
configuration schema.GroupVersionKind{Group:"kubeadm.k8s.io",
Version:"v1beta1", Kind:"ClusterConfiguration"}: error unmarshaling
JSON: while decoding JSON: json: unknown field "\u00a0 podSubnet”
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

[init] Using Kubernetes version: v1.13.1
[preflight] Running pre-flight checks
[preflight] Pulling images required for setting up a Kubernetes cluster
[preflight] This might take a minute or two, depending on the speed of
your internet connection
[preflight] You can also perform this action in beforehand using
'kubeadm config images pull’
[kubelet-start] Writing kubelet environment file with flags to file
"/var/lib/kubelet/kubeadm-flags.env”
[kubelet-start] Writing kubelet configuration to file
"/var/lib/kubelet/config.yaml”
[kubelet-start] Activating the kubelet service
[certs] Using certificateDir folder "/etc/kubernetes/pki”
[certs] Generating "etcd/ca" certificate and key
[certs] Generating "etcd/healthcheck-client" certificate and key
[certs] Generating "etcd/server" certificate and key
[certs] etcd/server serving cert is signed for DNS names
[localhost.localdomain localhost] and IPs [192.168.39.79 127 .0.0.1 ::1]
[certs] Generating "etcd/peer" certificate and key
[certs] etcd/peer serving cert is signed for DNS names
[localhost.localdomain localhost] and IPs [192.168.39.79 127 .0.0.1 ::1]
[certs] Generating "apiserver-etcd-client" certificate and key
[certs] Generating "ca" certificate and key
[certs] Generating "apiserver-kubelet-client" certificate and key
[certs] Generating "apiserver" certificate and key
[certs] apiserver serving cert is signed for DNS names
[localhost.localdomain kubernetes kubernetes.default
kubernetes.default.svc kubernetes.default.svc.cluster.local] and IPs
[10.96.0.1 192 .168.39.79]
[certs] Generating "front-proxy-ca" certificate and key
[certs] Generating "front-proxy-client" certificate and key
[certs] Generating "sa" key and public key
[kubeconfig] Using kubeconfig folder "/etc/kubernetes”
[kubeconfig] Writing "admin.conf" kubeconfig file
[kubeconfig] Writing "kubelet.conf" kubeconfig file
[kubeconfig] Writing "controller-manager.conf" kubeconfig file
[kubeconfig] Writing "scheduler.conf" kubeconfig file
[control-plane] Using manifest folder "/etc/kubernetes/manifests”
[control-plane] Creating static Pod manifest for "kube-apiserver”
[control-plane] Creating static Pod manifest for "kube-controller-
manager”
[control-plane] Creating static Pod manifest for "kube-scheduler”
[etcd] Creating static Pod manifest for local etcd in
"/etc/kubernetes/manifests”
[wait-control-plane] Waiting for the kubelet to boot up the control
plane as static Pods from directory "/etc/kubernetes/manifests". This
can take up to 4m0s
[apiclient] All control plane components are healthy after 24 .005638
seconds
[uploadconfig] storing the configuration used in ConfigMap "kubeadm-
config" in the "kube-system” Namespace

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

### 0x02. 配置 kubectl

在 Master上用 root用户执行下列命令来配置 kubectl：

```
[kubelet] Creating a ConfigMap "kubelet-config-1.13" in namespace kube-
system with the configuration for the kubelets in the cluster
[patchnode] Uploading the CRI Socket information
"/var/run/dockershim.sock" to the Node API object
"localhost.localdomain" as an annotation
[mark-control-plane] Marking the node localhost.localdomain as control-
plane by adding the label "node-role.kubernetes.io/master=''”
[mark-control-plane] Marking the node localhost.localdomain as control-
plane by adding the taints [node-role.kubernetes.io/master:NoSchedule]
[bootstrap-token] Using token: 26uprk.t7vpbwxojest0tvq
[bootstrap-token] Configuring bootstrap tokens, cluster-info ConfigMap,
RBAC Roles
[bootstraptoken] configured RBAC rules to allow Node Bootstrap tokens
to post CSRs in order for nodes to get long term certificate
credentials
[bootstraptoken] configured RBAC rules to allow the csrapprover
controller automatically approve CSRs from a Node Bootstrap Token
[bootstraptoken] configured RBAC rules to allow certificate rotation
for all node client certificates in the cluster
[bootstraptoken] creating the "cluster-info" ConfigMap in the "kube-
public” namespace
[addons] Applied essential addon: CoreDNS
[addons] Applied essential addon: kube-proxy
```
```
Your Kubernetes master has initialized successfully!
```
```
To start using your cluster, you need to run the following as a regular
user:
```
```
mkdir -p $HOME/.kube
sudo cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
sudo chown $(id -u):$(id -g) $HOME/.kube/config
```
```
You should now deploy a pod network to the cluster.
Run "kubectl apply -f [podnetwork].yaml" with one of the options listed
at:
https://kubernetes.io/docs/concepts/cluster-administration/addons/
```
```
You can now join any number of machines by running the following on
each node
as root:
```
```
kubeadm join 192 .168.39.79:6443 --token 26uprk.t7vpbwxojest0tvq --
discovery-token-ca-cert-hash
sha256:028727c0c21f22dd29d119b080dcbebb37f5545e7da1968800140ffe225b0123
```
```
[root@localhost ~]#
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

### 0x03. 安装Pod网络

安装 Pod网络是 Pod之间进行通信的必要条件，k8s支持众多网络方案，这里我们依然选用经典的

flannel方案

#### 首先设置系统参数：

```
然后在 Master节点上执行如下命令：
```
```
kube-flannel.yaml 文件下载地址：
```
#### 下载地址 1 （直接点击）

#### 下载地址 2 （直接点击）

一旦 Pod网络安装完成，可以执行如下命令检查一下 CoreDNS Pod此刻是否正常运行起来了，一旦其

正常运行起来，则可以继续后续步骤

同时我们可以看到主节点已经就绪：kubectl get nodes

## 添加 SLAVE节点

```
echo "export KUBECONFIG=/etc/kubernetes/admin.conf" >> /etc/profile
source /etc/profile
echo $KUBECONFIG
```
```
sysctl net.bridge.bridge-nf-call-iptables= 1
```
```
kubectl apply -f kube-flannel.yaml
```
```
kubectl get pods --all-namespaces -o wide
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

在两个 Slave节点上分别执行如下命令来让其加入Master上已经就绪了的 k8s集群：

如果 token忘记，则可以去 Master上执行如下命令来获取：

上述kubectl join命令的执行结果如下：

```
kubeadm join --token <token> <master-ip>:<master-port> --discovery-
token-ca-cert-hash sha256:<hash>
```
```
kubeadm token list
```
```
[root@localhost ~]# kubeadm join 192.168.39.79:6443 --token
yndddp.oamgloerxuune80q --discovery-token-ca-cert-hash
sha256:7a45c40b5302aba7d8b9cbd3afc6d25c6bb8536dd6317aebcd2909b0427677c8
[preflight] Running pre-flight checks
[discovery] Trying to connect to API Server "192.168.39.79:6443”
[discovery] Created cluster-info discovery client, requesting info from
"https://192.168.39.79:6443”
[discovery] Requesting info from "https://192.168.39.79:6443" again to
validate TLS against the pinned public key
[discovery] Cluster info signature and contents are valid and TLS
certificate validates against pinned roots, will use API Server
"192.168.39.79:6443”
[discovery] Successfully established connection with API Server
"192.168.39.79:6443”
[join] Reading configuration from the cluster...
[join] FYI: You can look at this config file with 'kubectl -n kube-
system get cm kubeadm-config -oyaml’
[kubelet] Downloading configuration for the kubelet from the "kubelet-
config-1.13" ConfigMap in the kube-system namespace
[kubelet-start] Writing kubelet configuration to file
"/var/lib/kubelet/config.yaml”
[kubelet-start] Writing kubelet environment file with flags to file
"/var/lib/kubelet/kubeadm-flags.env”
[kubelet-start] Activating the kubelet service
[tlsbootstrap] Waiting for the kubelet to perform the TLS Bootstrap...
[patchnode] Uploading the CRI Socket information
"/var/run/dockershim.sock" to the Node API object
"localhost.localdomain" as an annotation
```
```
This node has joined the cluster:
* Certificate signing request was sent to apiserver and a response was
received.
* The Kubelet was informed of the new secure connection details.
```
```
Run 'kubectl get nodes' on the master to see this node join the
cluster.
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 效果验证

#### 查看节点状态

```
查看所有 Pod状态
```
#### 好了，集群现在已经正常运行了，接下来看看如何正常的拆卸集群。

## 拆卸集群

#### 首先处理各节点：

#### 一旦节点移除之后，则可以执行如下命令来重置集群：

```
kubectl get nodes
```
```
kubectl get pods --all-namespaces -o wide
```
```
kubectl drain <node name> --delete-local-data --force --ignore-
daemonsets
kubectl delete node <node name>
```
```
kubeadm reset
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 安装 DASHBOARD

就像给elasticsearch配一个可视化的管理工具一样，我们最好也给 k8s集群配一个可视化的管理工具，

便于管理集群。

因此我们接下来安装 v1.10.0版本的 kubernetes-dashboard，用于集群可视化的管理。

#### 首先手动下载镜像并重新打标签：（所有节点）

```
安装 dashboard：
```
```
dashboard.yaml 文件下载地址：
```
#### 下载地址 1 （直接点击）

#### 下载地址 2 （直接点击）

```
查看 dashboard的 pod是否正常启动，如果正常说明安装成功:
```
```
docker pull registry.cn-qingdao.aliyuncs.com/wangxiaoke/kubernetes-
dashboard-amd64:v1.10.0
docker tag registry.cn-qingdao.aliyuncs.com/wangxiaoke/kubernetes-
dashboard-amd64:v1.10.0 k8s.gcr.io/kubernetes-dashboard-amd64:v1.10.0
docker image rm registry.cn-qingdao.aliyuncs.com/wangxiaoke/kubernetes-
dashboard-amd64:v1.10.0
```
```
kubectl create -f dashboard.yaml
```
```
kubectl get pods --namespace=kube-system
```
```
[root@k8s-master ~]# kubectl get pods --namespace=kube-system
NAME READY STATUS RESTARTS
AGE
coredns-86c58d9df4-4rds2 1 /1 Running 0
81m
coredns-86c58d9df4-rhtgq 1 /1 Running 0
81m
etcd-k8s-master 1 /1 Running 0
80m
kube-apiserver-k8s-master 1 /1 Running 0
80m
kube-controller-manager-k8s-master 1 /1 Running 0
80m
kube-flannel-ds-amd64-8qzpx 1 /1 Running 0
78m
kube-flannel-ds-amd64-jvp59 1 /1 Running 0
77m
kube-flannel-ds-amd64-wztbk 1 /1 Running 0
78m
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
查看 dashboard的外网暴露端口
```
#### 生成私钥和证书签名：

#### 生成SSL证书：

```
然后将生成的 dashboard.key 和 dashboard.crt置于路径 /home/share/certs下，该路
径会配置到下面即将要操作的
```
dashboard-user-role.yaml文件中

```
创建 dashboard用户
```
dashboard-user-role.yaml 文件下载地址：

#### 下载地址 1 （直接点击）

#### 下载地址 2 （直接点击）

```
kube-proxy-crr7k 1 /1 Running 0
81m
kube-proxy-gk5vf 1 /1 Running 0
78m
kube-proxy-ktr27 1 /1 Running 0
77m
kube-scheduler-k8s-master 1 /1 Running 0
80m
kubernetes-dashboard-79ff88449c-v2jnc 1 /1 Running 0
21s
```
```
kubectl get service --namespace=kube-system
```
#### NAME TYPE CLUSTER-IP EXTERNAL-IP

#### PORT(S) AGE

```
kube-dns ClusterIP 10 .96.0.10 <none>
53 /UDP,53/TCP 5h38m
kubernetes-dashboard NodePort 10 .99.242.186 <none>
443 :31234/TCP 14
```
```
openssl genrsa -des3 -passout pass:x -out dashboard.pass.key 2048
openssl rsa -passin pass:x -in dashboard.pass.key -out dashboard.key
rm dashboard.pass.key
openssl req -new -key dashboard.key -out dashboard.csr【如遇输入，一路回⻋
即可】
```
```
openssl x509 -req -sha256 -days 365 -in dashboard.csr -signkey
dashboard.key -out dashboard.crt
```
```
kubectl create -f dashboard-user-role.yaml
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
获取登陆token
```
token既然生成成功，接下来就可以打开浏览器，输入 token来登录进集群管理⻚面：

```
kubectl describe secret/$(kubectl get secret -nkube-system |grep
admin|awk '{print $1}') -nkube-system
```
```
[root@k8s-master ~]# kubectl describe secret/$(kubectl get secret -
nkube-system |grep admin|awk '{print $1}') -nkube-system
Name: admin-token-9d4vl
Namespace: kube-system
Labels: <none>
Annotations: kubernetes.io/service-account.name: admin
kubernetes.io/service-account.uid: a320b00f-07ed-11e9-
93f2-000c2978f207
```
```
Type: kubernetes.io/service-account-token
```
```
Data
====
ca.crt: 1025 bytes
namespace: 11 bytes
token:
eyJhbGciOiJSUzI1NiIsImtpZCI6IiJ9.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2
NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlL
XN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJh
ZG1pbi10b2tlbi05ZDR2bCIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2Vydml
jZS1hY2NvdW50Lm5hbWUiOiJhZG1pbiIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bn
Qvc2VydmljZS1hY2NvdW50LnVpZCI6ImEzMjBiMDBmLTA3ZWQtMTFlOS05M2YyLTAwMGMyO
Tc4ZjIwNyIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTphZG1p
biJ9.WbaHx-
BfZEd0SvJwA9V_vGUe8jPMUHjKlkT7MWJ4JcQldRFY8Tdpv5GKCY25JsvT_GM3ob303r0yE
6vjQdKna7EfQNO_Wb2j1Yu5UvZnWw52HhNudHNOVL_fFRKxkSVjAILA_C_HvW6aw6TG5h7z
HARgl71I0LpW1VESeHeThipQ-pkt-Dr1jWcpPgE39cwxSgi-
5qY4ssbyYBc2aPYLsqJibmE-
KUhwmyOheF4Lxpg7E3SQEczsig2HjXpNtJizCu0kPyiR4qbbsusulH-
kdgjhmD9_XWP9k0BzgutXWteV8Iqe4-uuRGHZAxgutCvaL5qENv4OAlaArlZqSgkNWw
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# ELASTICSEARCH集群部署

## 环境准备

#### 节点准备

本文准备搭建 **双节点** Elasticsearch集群（用双节点仅仅是做演示），因此这里准备了两台 **Linux**

**CentOS 7.4 64bit** 机器：

#### 节点 1 ：192.168.31.8

#### 节点 2 ：192.168.31.9

```
Elasticsearch 安装包准备
```
这里下载的是：6.4.2版

#### 安装目录准备

这里拟将 Elasticsearch安装在 /opt/elasticsearch 目录下：

## ELASTICSEARCH 集群配置

需要修改两个节点上的配置文件 elasticsearch.yml

#### 节点 1 配置

```
wget
https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-
6.4.2.tar.gz
```
```
mkdir /opt/elasticsearch
将压缩包复制到该目录下并解压
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 节点 2 配置

## 集群启动前准备

#### 创建用户及用户组

由于 Elasticsearch不能以 root用户启动，因此需要添加非 root用户：

```
cluster.name: codesheep # 集群名称
node.name: sheep1 # 节点名
network.host: 192 .168.31.8 # 绑定的节点 1 地址
network.bind_host: 0 .0.0.0 # 此项不设置你试试本机可能访问不了啊
discovery.zen.ping.unicast.hosts: ["192.168.31.8","192.168.31.9"] #
hosts列表
discovery.zen.minimum_master_nodes: 1
```
```
## 如下配置是为了解决 Elasticsearch可视化工具 dejavu的跨域问题！若不用可视化工具
则可省略之
http.port: 9200
http.cors.allow-origin: "http://192.168.199.76:1358"
http.cors.enabled: true
http.cors.allow-headers : X-Requested-With,X-Auth-Token,Content-
Type,Content-Length,Authorization
http.cors.allow-credentials: true
```
```
cluster.name: codesheep # 集群名称
node.name: sheep1 # 节点名
network.host: 192 .168.31.9 # 绑定的节点 2 地址
network.bind_host: 0 .0.0.0
discovery.zen.ping.unicast.hosts: ["192.168.31.8","192.168.31.9"] #
hosts列表
discovery.zen.minimum_master_nodes: 1
```
```
## 如下配置是为了解决 Elasticsearch可视化工具 dejavu的跨域问题！若不用可视化工具
则可省略之
http.port: 9200
http.cors.allow-origin: "http://192.168.199.76:1358"
http.cors.enabled: true
http.cors.allow-headers : X-Requested-With,X-Auth-Token,Content-
Type,Content-Length,Authorization
http.cors.allow-credentials: true
```
```
groupadd es
useradd es -g es
chown -R es:es ./elasticsearch-6.4.2
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 关闭防火墙

## 启动 ELASTICSEARCH集群

#### 切换用户

#### 分别在 节点 1 和 节点 2 上启动ES服务

```
浏览器访问：http://ip:9200/ 查看启动效果
```
#### 命令行查看集群信息

systemctl stop firewalld
systemctl disable firewalld

su es

cd bin
./elasticsearch // 若要后台启动，则加-d参数

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
利用可视化工具 dejavu查看集群信息
```
关于 Elasticsearch集群可视化管理工具的上手，可以参考我的前文：《一文上手 Elasticsearch常用可

视化管理工具》

#### 接下来插入两条数据

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 查看数据的入库效果

curl -X PUT 'localhost:9200/accounts/person/1' -d '
{
"user": "张三",
"title": "工程师",
"desc": "数据库管理"
}'

curl -X PUT 'localhost:9200/accounts/person/1' -d '
{
"user": "赵四",
"title": "设计师",
"desc": "UI设计"
}'

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### OK， 索引 / 类型 / 文档 一目了然！

```
若在 Elasticsearch集群 安装/启动 过程 中有任何奇葩 问题/错误 的话，可以参考这篇文章：
《CentOS7上ElasticSearch安装填坑记》吧，里面记录了一些踩过的坑！
```
## 安装IK分词器

```
在 Elasticsearch的世界中，插件是很重要的一部分，很多功能都可以通过插件来实现，因此下面
就以常用的 IK分词器插件 的安装为例，来操作一下 Elasticsearch插件的安装
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

#### 分词技术是搜索技术的基石，而 IK分词器是比较经典的一个，接下来尝试安装一下吧

#### IK分词器版本与 ES版本对应，不能搞错，可在 这里查看

#### 下载 IK分词器插件

#### 解压 / 安装

新建目录 /opt/elasticsearch/elasticsearch-6.4.2/plugins/elasticsearch-analysis-ik-

6.4.2

再将 zip包置于上述目录下并解压：

```
unzip elasticsearch-analysis-ik-6.4.2.zip
```
```
重启 Elasticsearch集群
```
重启 Elasticsearch集群，若发现如下内容，这说明插件安装成功：

#### 怎么样，很简单吧，说到底就是一个解压放置的过程而已。

```
wget https://github.com/medcl/elasticsearch-analysis-
ik/releases/download/v6.4.2/elasticsearch-analysis-ik-6.4.2.zip
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# ZOOKEEPER安装部署

## 准备安装包

这里使用的是3.6.1版，下载的是apache-zookeeper-3.6.1-bin.tar.gz压缩包，并将其放在

了/root目录下

## 解压并安装

在/usr/local/下创建zookeeper文件夹并进入

2 、将ZooKeeper安装包解压到/usr/local/zookeeper中即可

解压完之后，/usr/local/zookeerper目录中会出现一个apache-zookeeper-3.6.1-bin的目录

## 创建DATA目录

这里直接在/usr/local/zookeeper/apache-zookeeper-3.6.1-bin目录中创建一个data目录

```
cd /usr/local/
mkdir zookeeper
cd zookeeper
```
```
[root@localhost zookeeper]# tar -zxvf /root/apache-zookeeper-3.6.1-
bin.tar.gz -C ./
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

等下该data目录地址要配到ZooKeeper的配置文件中：

## 创建配置文件并修改

进入到zookeeper的conf目录，复制zoo_sample.cfg得到zoo.cfg：

修改配置文件zoo.cfg，将其中的dataDir修改为上面刚创建的data目录，其他选项可以按需配置

```
[root@localhost apache-zookeeper-3.6.1-bin]# cd conf/
[root@localhost conf]# cp zoo_sample.cfg zoo.cfg
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 启动ZOOKEEPER

#### 启动后可以通过如下命令来检查启动后的状态：

从图中也可以看出zookeeper默认会绑定端口 2181 。

```
[root@localhost apache-zookeeper-3.6.1-bin]# ./bin/zkServer.sh start
```
```
[root@localhost apache-zookeeper-3.6.1-bin]# ./bin/zkServer.sh status
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 配置环境变量

#### 编辑配置文件：

尾部加入ZooKeeper的bin路径配置即可

最后执行 source /etc/profile使环境变量生效即可。

## 设置开机自启

首先进入/etc/rc.d/init.d目录，创建一个名为zookeeper的文件，并赋予执行权限

接下来编辑zookeeper文件，并在其中加入如下内容：

#### 最后加入开机启动即可：

```
vim /etc/profile
```
```
export ZOOKEEPER_HOME=/usr/local/zookeeper/apache-zookeeper-3.6.1-bin
export PATH=$PATH:$ZOOKEEPER_HOME/bin
```
```
[root@localhost ~]# cd /etc/rc.d/init.d/
[root@localhost init.d]# touch zookeeper
[root@localhost init.d]# chmod +x zookeeper
```
```
#!/bin/bash
#chkconfig:- 20 90
#description:zookeeper
#processname:zookeeper
ZOOKEEPER_HOME=/usr/local/zookeeper/apache-zookeeper-3.6.1-bin
export JAVA_HOME=/usr/local/java/jdk1.8.0_161 # 此处根据你的实际情况更换对
应
case $1 in
start) su root $ZOOKEEPER_HOME/bin/zkServer.sh start;;
stop) su root $ZOOKEEPER_HOME/bin/zkServer.sh stop;;
status) su root $ZOOKEEPER_HOME/bin/zkServer.sh status;;
restart) su root $ZOOKEEPER_HOME/bin/zkServer.sh restart;;
*) echo "require start|stop|status|restart" ;;
```
```
esac
```
```
chkconfig --add zookeeper
chkconfig zookeeper on
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# 消息队列KAFKA安装部署

## 首先准备ZOOKEEPER服务

因为Kafka的运行环境依赖于ZooKeeper，所以首先得安装并运行ZooKeeper。

#### 这个可以参考上面一节的内容。

## 准备KAFKA安装包

这里下载的是2.5.0版：kafka_2.12-2.5.0.tgz，将下载后的安装包放在了/root目录下

## 解压并安装

在/usr/local/下创建kafka文件夹并进入

2 、将Kafka安装包解压到/usr/local/kafka中即可

解压完之后，/usr/local/kafka目录中会出现一个kafka_2.12-2.5.0的目录

## 创建LOGS目录

这里直接在/usr/local/kafka/kafka_2.12-2.5.0目录中创建一个logs目录

等下该logs目录地址要配到Kafka的配置文件中。

```
cd /usr/local/
mkdir kafka
cd kafka
```
```
[root@localhost kafka]# tar -zxvf /root/kafka_2.12-2.5.0.tgz -C ./
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 修改配置文件

进入到Kafka的config目录，编辑配置文件server.properties

修改配置文件，一是将其中的log.dirs修改为上面刚创建的logs目录，其他选项可以按需配置

另外关注一下连接ZooKeeper的相关配置，根据实际情况进行配置：

```
[root@localhost kafka_2.12-2.5.0]# cd config/
[root@localhost config]# vim server.properties
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

## 启动KAFKA

#### 执行如下命令即可：

```
如果需要后台启动，则加上-daemon参数即可
```
## 实验验证

首先创建一个名为codesheep的topic：

```
./bin/kafka-server-start.sh ./config/server.properties
```
```
./bin/kafka-topics.sh --create --bootstrap-server localhost:9092 --
replication-factor 1 --partitions 1 --topic codesheep
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

创建完成以后，可以使用命令来列出目前已有的topic列表

接下来创建一个 **生产者** ，用于在codesheep这个topic上生产消息：

而后接着创建一个 **消费者** ，用于在codesheep这个topic上获取消息：

#### 此时生产者发出的消息，在消费者端可以获取到：

```
./bin/kafka-topics.sh --list --bootstrap-server localhost:9092
```
```
./bin/kafka-console-producer.sh --bootstrap-server localhost:9092 --
topic codesheep
```
```
./bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --
topic codesheep
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，


# 注意事项

#### 实验过程中如果出现一些诸如客户端不能连通或访问等问题，可尝试考虑关闭防火墙：

```
systemctl stop firewalld.service
systemctl disable firewalld.service
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

# 持续更新中...

#### 该PDF文档会持续更新，有新东⻄再往里加，有些东⻄也可以再继续优化。由于个人精力和能力有限，

#### 难免会有疏漏和不当的地方，还希望多多谅解。

#### 另外， 联系作者、提意⻅，可直接扫码联系，一起交流进步：

```
本文档在 Github开源项目：github.com/hansonwang99/JavaCollection 中已收录，有详细
自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
有详细自学编程学习路线、面试题和面经、编程资料及系列技术文章等，资源持续更新中...
```
```
本文档在 Github开源项目：https://github.com/hansonwang99/JavaCollection 中已收录，
```

****