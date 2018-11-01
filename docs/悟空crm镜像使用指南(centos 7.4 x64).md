### 悟空crm镜像使用指南(centos 7.4 x64)

![](https://upload-images.jianshu.io/upload_images/3778244-19e7692339c7a45e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 简介

悟空CRM是一款永久开源免费的CRM管理系统,悟空CRM是使用PHP和Mysql开发,基于B/S架构的CRM管理软件

### 悟空crm镜像系统环境介绍

- 操作系统: centos 7.4 x64
- 悟空crm版本： 0.5.5 
- 登录界面: 输入服务器的ip或者绑定的域名即可
- 数据库管理地址: ip/phpmyadmin/
- mysql账号：root
- mysql密码：Yuncan123
- 账号: admin
- 密码: Yuncan123

### 镜像推荐ecs配置

-  最低: 1核心1g内存
- 推荐: 1核心4g内存

### 安全组相关

请打开以下安全组端口

-80
- 22

### 首次使用

当安装镜像服务器启动完成之后直接在浏览器中输入访问ip

之后登陆，输入账号:admin 密码:Yuncan123

![](https://upload-images.jianshu.io/upload_images/3778244-fe465da9bb481098.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

登陆之后记住要修改登陆的密码，点击右上角的头像选择个人资料在箭头方向输入你的新密码

![](https://upload-images.jianshu.io/upload_images/3778244-0e8bd49660e77640.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

之后修改数据库的密码，在浏览器中输入ip/phpmyadmin打开phpmyadmin数据库管理工具之后输入账号root密码Yuncan123登陆

![](https://upload-images.jianshu.io/upload_images/3778244-65f2779ee07e5af9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

接着点击修改密码来修改密码、

![](https://upload-images.jianshu.io/upload_images/3778244-dee990f7ad1a4b1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





### 镜像已知问题

目前没有，欢迎反馈

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20181101: v1.0首个版本

### 云璨，值得信赖的上云专家！

### 云璨官网http://www.yuncan.com/