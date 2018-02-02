# gooderp(ubuntu 16.04)使用指南

### gooderp介绍

GoodERP 基于 Python 和 Postgresql 技术，是 github 上以 AGPL3 协议开发的自由软件，实现了中国中小企业关注的财务+进销存的核心功能，并支持二次开发模块化扩展，可能是中国用户数最多的开源 ERP

### 系统环境概述

- 操作系统：ubuntu 16.04 64位 
- gooderp管理用户名和用户组名：gooderp
- 安装主目录：/home/gooderp
- 初始化用户邮箱：gooderp@gooderp.com
- 密码：Yuncan1803
- 访问方式：ip:8069
- ubuntu系统更新日期：2018-02-02 
- 安全组相关：开放22 8069端口
- gooderp使用教学视频：http://space.bilibili.com/174336503#/channel/index 
- 官网：http://www.gooderp.org/ 

 ### 对gooderp的常用操作

默认gooderp开机自启

- 查看gooderp运行状态：systemctl status gooderp
- 启动gooderp：systemctl start gooderp
- 关闭gooderp：systemctl stop gooderp
- 重启gooderp：systemctl restart gooderp


### 对postgresql的常用操作

- 启动postgresql：systemctl start postgresql
- 关闭postgresql：systemctl stop postgresql
- 重启postgresql：systemctl restart postgresql
- 查看postgresql运行状态：systemctl status postgresql

### 初次使用gooderp系统镜像

首先使用服务器ip:8069打开gooderp web界面，之后输入默认的邮箱名:gooderp@gooderp.com和密码Yuncan1803登录

![](http://upload-images.jianshu.io/upload_images/3778244-83070c35009ceb13.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)

点击设置->用户->administrator

![](http://upload-images.jianshu.io/upload_images/3778244-1d428d8a1e804a4e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)

点击编辑

![](http://upload-images.jianshu.io/upload_images/3778244-c3cdbc7018483529.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)
接着可以修改邮箱，密码账号名

![](http://upload-images.jianshu.io/upload_images/3778244-ad234df72ff92c0f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)

### 已知问题

因为是使用nvm和pyenv管理python和nodejs所以注意当要切换用户时先切换到到/home/gooderp目录不然会报权限错误 

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

V1.0
V2.0(解决了一些错误，更新系统日期:20180202，优化了系统环境)

### 云璨你的专属私人服务
### 云璨官网：http://www.yuncan.com/ 

