# MailArchiva 镜像使用指南

### MailArchiva简介

MAILARCHIVA是一个功能强大，全功能的电子邮件归档（电子邮件归档）和Microsoft Exchange等邮件系统符合性解决方案。它存储长期贮存所有传入，传出和内部电子邮件。一个基于Web的用户界面

### MailArchiva镜像系统环境介绍

**MailArchiva安装概述**
- Max heap size：1583M
- 版本：5.4.1

**系统版本介绍**：采用阿里云公共镜像centos7.4 64位
**系统更新日期**：20180117

**管理命令**
- 启动MailArchiva：sudo /etc/init.d/mailarchiva start
- 重启MailArchiva：sudo /etc/init.d/mailarchiva restart
- 停止MailArchiva：sudo /etc/init.d/mailarchiva stop
- 查看MailArchiva运行状态：sudo /etc/init.d/mailarchiva status

**安全组相关**
打开以下端口
(22|8090|8091)

### 初始化安装指南

为了安全，故本镜像不做初始化的安装
当安装完本镜像且ECS启动完成之后，在浏览器中使用ip:8090的方式来访问MailArchiva的安装页面
![](http://upload-images.jianshu.io/upload_images/3778244-e92ecf59c0a0173f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
点击next是协议界面，点击I Agree to the terms of the above license 之后点击下一步
![](http://upload-images.jianshu.io/upload_images/3778244-2ba8b1719bd06d46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
接下来我们设置管理员的密码等一些信息，注意，管理员密码和加密邮件密码是不能一样的，设置好之后点击下一步
![](http://upload-images.jianshu.io/upload_images/3778244-9cfe6758d2970c2a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
接着设置一些文件的路径，就像下面这样，接着点击下一步
![](http://upload-images.jianshu.io/upload_images/3778244-49897adbfb937160.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
上面我们设置的是应用程序的一些路径，下面我们设置的是数据存储的路径，设置好之后点击下一步
![](http://upload-images.jianshu.io/upload_images/3778244-0d0587befa87eb0f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
接着来是设置MailArchiva的账号
![](http://upload-images.jianshu.io/upload_images/3778244-7adfe9197c5c1ea9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
安装完成，点击login登录
![](http://upload-images.jianshu.io/upload_images/3778244-f64c43722ff90430.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)

### 镜像已知问题

小内存机器启动的时候可能会比较慢，默认开机自动启动程序，请等待一段时间后重新访问，若一直不能访问请执行`sudo /etc/init.d/mailarchiva restart`命令

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20180117 V1.0

> 云璨，值得信赖的上云专家！
> 云璨官网http://www.yuncan.com/
