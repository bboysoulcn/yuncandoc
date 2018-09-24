### jumpserver镜像使用指南(centos 7.4 x64)

![](https://upload-images.jianshu.io/upload_images/3778244-0991af32773e8df8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 简介

Jumpserver 是全球首款完全开源的堡垒机,使用GNU GPL v2.0开源协议,是符合 4A 的专业运维安全审计系统。

### jumpserver镜像系统环境介绍

- 操作系统: centos 7.4 x64
- jumpserver版本：1.4.1
- 默认账号和密码: admin/admin
- 默认数据库账号密码: jumpserver/Yuncan123
- 默认数据库root密码: Yuncan123

### 镜像推荐ecs配置

-  最低: 1核心2g内存
- 推荐: 1核心4g内存

### 安全组相关

请打开以下安全组端口

- 22
- 80
- 2222

### 首次使用

首先ssh进入你的服务器，再/root下面有两个脚本start.sh 和stop.sh

执行`./start.sh` 来启动jumpserver
执行`./stop.sh` 来停止jumpserver

如果你想管理windows资产请执行

~~~bash
docker run --name jms_guacamole -d \
  -p 8081:8080 -v /opt/guacamole/key:/config/guacamole/key \
  -e JUMPSERVER_KEY_DIR=/config/guacamole/key \
  -e JUMPSERVER_SERVER=http://<请填写服务器的公网ip或者域名> \
  jumpserver/guacamole:latest
~~~

之后再浏览器输入你的服务器ip登陆，默认账号和密码是admin/admin

![](https://upload-images.jianshu.io/upload_images/3778244-73a4f6dcb5f50c05.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

记住进入之后请修改默认的账号和密码

### 镜像已知问题

- 目前没有欢迎反馈

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20180925: 首个版本

### 云璨，值得信赖的上云专家！

### 云璨官网http://www.yuncan.com/