![](http://upload-images.jianshu.io/upload_images/3778244-7362bc5a75f45212.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# open-falcon使用指南

### open-falcon介绍

open-falcon是一个开源，可扩展，高性能，用户友好的监测系统，项目由小米启动，目前最高版本是0.2，open-falcon后端使用golang开发，dashboard和仪表板使用python开发。

### open-falcon镜像系统环境介绍

- 操作系统：centos7.4
- open-falcon安装目录：`/home/work/open-falcon/`
- 使用的数据库：mariadb
- 数据库密码：Yuncan1803
- 访问方式：ip:8081
- 默认不创建任何用户
- 安全组打开下面端口(22|8081)
- 系统更新日期:20180208

### 初始化使用指南


当你安装完镜像并且启动成功之后，首先登录服务器启动open-falcon
`ssh root@ip`
接着执行脚本开启open-falcon
`./start.sh`
之后使用ip:8081访问open-falcon的dashboard

![](http://upload-images.jianshu.io/upload_images/3778244-902cbc69e249ee44.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

默认openfalcon没有任何用户，你创建的第一个root用户就是openfalcon的管理员用户，点击sign up，创建填入相关信息，如果你要创建管理员用户，那么`Login Name(a-zA-Z0-9_.):`要写root

![](http://upload-images.jianshu.io/upload_images/3778244-60006ca83574f604.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 修改数据库密码

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 云璨你的专属私人服务

### 云璨官网：http://www.yuncan.com/
