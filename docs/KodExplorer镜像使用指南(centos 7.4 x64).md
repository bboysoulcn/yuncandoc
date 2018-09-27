### KodExplorer镜像使用指南(centos 7.4 x64)

![](https://upload-images.jianshu.io/upload_images/3778244-9c476cf75d204cfc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 简介

KodExplorer可道云，原名芒果云，是基于Web技术的私有云和在线文档管理解决方案。Kod，读音通code，意为“代码，编码”，中文名为“可道”。

### KodExplorer镜像系统环境介绍

- 操作系统: centos 7.4 x64
- KodExplorer版本：4.35

### 镜像推荐ecs配置

-  推荐: 1核心2g内存
- 最低: 1核心1g内存

### 安全组相关

请打开以下安全组端口

- 22
- 80

### 首次使用

因为阿里云镜像的审核问题，不允许出现777权限的文件夹，但是可道云的站点文件需要777权限，所以首次使用的时候需要进入服务器修改站点文件夹的权限。

首先ssh登入服务器中，之后执行

`chmod -Rf  777 /data/wwwroot/kodexplorer`

不然在浏览器访问的时候会出现下面界面

![](https://upload-images.jianshu.io/upload_images/3778244-378b2457f16157c0.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


如果修改完成权限，在浏览器输入你的服务器ip会出现下面这个页面

![](https://upload-images.jianshu.io/upload_images/3778244-322f9d9d16addd19.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在输入框中输入两次密码之后会进入下面这个登陆界面

![](https://upload-images.jianshu.io/upload_images/3778244-51182e00973066e6.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

输入admin和你设置的账号登陆完成会出现下面这个页面

![](https://upload-images.jianshu.io/upload_images/3778244-429b2b0ae57aaa72.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



### 镜像已知问题

- 因为阿里云审核问题导致站点文件夹不能是777权限

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20180915: 首个版本
- 20180927: v1.2 站点权限修改位755

### 云璨，值得信赖的上云专家！

### 云璨官网http://www.yuncan.com/