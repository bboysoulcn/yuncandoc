# MailArchiva 镜像使用指南(windows server 2008)

### MailArchiva简介

MAILARCHIVA是一个功能强大，全功能的电子邮件归档（电子邮件归档）和Microsoft Exchange等邮件系统符合性解决方案。它存储长期贮存所有传入，传出和内部电子邮件。一个基于Web的用户界面

### MailArchiva镜像系统环境介绍

**MailArchiva安装概述**
- 默认账号admin
- 默认密码：Yuncan1803
- 加密邮件密码: Yuncan2
- Max heap size：2048M
- 版本：5.4.1

**系统版本介绍**：采用阿里云公共镜像windows server 2008 r2企业版 64位中文版
**系统更新日期**：20180119

**安全组相关**
打开以下端口
(3389|8090)

### 简单的启动关闭管理

使用vnc或者阿里云的远程连接进入服务器，右键点击右下角的圆圈标志
![](http://upload-images.jianshu.io/upload_images/3778244-06fc72a981b73ce7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
就可以进行简单的开启关闭操作，默认开机程序自动启动


### 初始化使用

**修改密码**

使用浏览器ip:8090访问mailarchiva的登录界面
默认账号admin
默认密码：Yuncan1803
登录之后修改密码，点击配置login修改admin的密码
输入两次密码之后点击保存
![](http://upload-images.jianshu.io/upload_images/3778244-bb7f85a7c97065bf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)


**修改域**
点击配置，在域选项卡中输入域名之后点击保存

![](http://upload-images.jianshu.io/upload_images/3778244-91d2cfeb05c2e072.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)


### 镜像已知问题

小内存机器启动的时候可能会比较慢，默认开机自动启动程序，请尽量使用2g以上的内存的阿里云ecs

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20180119 V1.0

> 云璨，值得信赖的上云专家！
> 云璨官网http://www.yuncan.com/
