### 分布式任务调度平台XXL-JOB镜像使用指南(centos 7.6 x64)

![](https://upload-images.jianshu.io/upload_images/3778244-1b935f3722fd6e02.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 简介

XXL-JOB是一个轻量级分布式任务调度平台，其核心设计目标是开发迅速、学习简单、轻量级、易扩展。现已开放源代码并接入多家公司线上产品线，开箱即用。

### XXL-JOB镜像系统环境介绍

- 操作系统: centos 7.6 x64
- XXL-JOB版本： 2.0.1
- 登录界面: ip:8080/xxl-job-admin/
- mysql版本: 8.0.13
- mysql 账号: root
- mysql 密码: Yuncan@123

### 镜像推荐ecs配置

- 最低: 1核心2g内存
- 推荐: 1核心4g内存

### 安全组相关

请打开以下安全组端口

- 8080
- 22

### 首次使用

首次使用先ssh登录服务器，之后执行下面的命令

`cd /home/xxl-job-admin && ./start.sh && cd /home/xxl-job-executor/ && ./start.sh`

接着在自己电脑的浏览器上输入

`ip:8080/xxl-job-admin/`

就可以看到登录界面

![](https://upload-images.jianshu.io/upload_images/3778244-b497e4326af96f6d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


输入账号admin密码123456即可登录成功

![](https://upload-images.jianshu.io/upload_images/3778244-53658db86dccf9a0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

详细使用教程请看

`http://www.xuxueli.com/xxl-job/`


### 镜像已知问题

目前没有，欢迎反馈

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20190106: v1.0首个版本

### 云璨，值得信赖的上云专家！

### 云璨官网http://www.yuncan.com/