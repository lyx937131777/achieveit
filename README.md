# achieveit
软件开发实践小组项目

框架:

前端Vue + 后端SpringBoot 

本地部署方式：

0.首先需要安装jdk+mysql

1.将项目克隆到本地(建议克隆到D:\IDEA\Project 目录下)

2.打开mysql，新建scis，设置账号密码（建议用root 和 123456）

3.进入scis，输入【create Database scis;】并执行（闪电图标）

![image](https://github.com/lyx937131777/achieveit/blob/master/images/mysql.png)

4.用IDEA打开项目，进入src/main/resources

5.打开application.yml 将红框内改为自己的数据库账号和密码（如果第2步相同则不用改）

![image](https://github.com/lyx937131777/achieveit/blob/master/images/path.png)

6.打开application-dev.yml  将file内改为自己的目录（如果第1步相同则不用改）

![image](https://github.com/lyx937131777/achieveit/blob/master/images/path2.png)

7.打开src/main/java/com/cohy/scis/ScisApplication 并运行

![image](https://github.com/lyx937131777/achieveit/blob/master/images/start.png)
