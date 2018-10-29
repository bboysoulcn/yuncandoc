### gitlab镜像使用指南(centos 7.4 x64)

![](https://upload-images.jianshu.io/upload_images/3778244-25fc8a1b5295a0bf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 简介

GitLab是由GitLab Inc.开发，使用MIT许可证的基于网络的Git仓库管理工具，且具有wiki和issue跟踪功能。

### gitlab镜像系统环境介绍

- 操作系统: centos 7.4 x64
- gitlab版本：11.3.0

### 镜像推荐ecs配置

-  最低: 1核心4g内存
- 推荐: 2核心4g内存

### 安全组相关

请打开以下安全组端口

- 22
- 80

### 首次使用

小内存机器需要在服务器启动之后等待较长时间才可以打开gitlab，不然会报502错误

正常情况下在浏览器中输入你服务器的ip会出现下面的界面

![](https://upload-images.jianshu.io/upload_images/3778244-40df4b7deeeb4118.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在输入框中输入你要设置的管理员密码之后确定跳到下面这个界面

![](https://upload-images.jianshu.io/upload_images/3778244-386fbc0cd3388164.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

输入root和你设置的密码登陆，就可以进入主界面

![](https://upload-images.jianshu.io/upload_images/3778244-d37ff39289a68cda.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



### 镜像已知问题

- 小内存机器打开可能会报502错误，请等待一段时间刷新，如果一直502请登陆服务器输入`sudo gitlab-ctl reconfigure`来重新开启gitlab

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20180927: v1.0首个版本

### 云璨，值得信赖的上云专家！

### 云璨官网http://www.yuncan.com/