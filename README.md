# 师生博客系统

#### 1、项目环境

SpringBoot 2.1.5.RELEASE

Maven 3.5.2

Tomcat 8

jdk1.8

#### 2、技术栈

技术栈：Spring+Springmvc+Mybatis+SpringBoot+Mysql+Redis+Thymeleaf+Kafka+ElasticSearch+Quartz+Caffine

#### 3、项目启动方式

配置mysql、七牛云等信息。

打开zookeeper、kafka、elasticsearch、redis。



F:\JavaTools\redis-2.8.9>redis-server.exe redis.windows.conf

F:\JavaTools\kafka_2.12-2.3.0>bin\windows\zookeeper-server-start.bat config\zookeeper.properties

F:\JavaTools\kafka_2.12-2.3.0>bin\windows\kafka-server-start.bat config\server.properties

打开es的bin目录，打开es.bat

开发环境使用application-dev，生产环境使用application-pro，生产环境需要重新配置文件目录地址

#### 4、提供的账号
权限分为普通用户、管理员<br/>
2017331200029-2017331200038 学生账号　　密码：123456<br/>
29-33为男同学，34-38为女同学<br/>
29、30、34、35为管理员账号<br/>

20170029-20170031 老师账号　　密码：123456<br/>
29-30为男老师，31为女老师<br/>
老师账号均为管理员<br/>