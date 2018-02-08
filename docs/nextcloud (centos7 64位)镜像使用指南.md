![](http://upload-images.jianshu.io/upload_images/3778244-21b13624dfedcddb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


# nextcloud (centos7 64位)镜像使用指南

### nextcloud简介

Nextcloud是ownCloud的衍生版本，是一个开源的网盘解决方案，可以很方便得部署在云服务器上使用，同时提供了各个平台的客户端，方便用户同步使用

### nextcloud镜像系统环境介绍

为了方便用户管理云服务器所以在镜像里安装了宝塔面板方便用户对esc进行图形化操作

预装的软件

- nginx 1.12
- php 5.6
- 宝塔面板5.5
- nextcloud 12.0.5

系统更新日期:20180126
安全组打开下面端口(22|80|8888)

### 宝塔面板相关

- 宝塔面板用户名：Yuncan
- 宝塔面板密码：Yuncan1803
- 宝塔面板访问方式：ip+端口8888

### nextcloud相关

- nextcloud数据库：sqlite
- nextcloud用户名：Yuncan
- nextcloud密码：Yuncan1803
- nextcloud数据目录：/www/wwwroot/nextcloud/data


### 初始化使用

安装好镜像之后，如果马上访问网站可能会遇到404的错误，那是因为程序没有启动完成的问题，等待一段时间刷新即可进去

![](http://upload-images.jianshu.io/upload_images/3778244-8c2ff3de45344a70.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)

因为配置环境机器和安装镜像机器不是同一ip，所以会出现这个问题，点击添加为信任域名即可

![](http://upload-images.jianshu.io/upload_images/3778244-bca19fac0dabda5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击是，之后我们修改nextcloud的账号和密码

![](http://upload-images.jianshu.io/upload_images/3778244-c02f09bf3c19ba9b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/720)

点击个人，输入当前密码Yuncan1803，新密码，再点击修改密码即可修改成功

### 镜像使用问题反馈

如果在镜像使用的时候出现任何问题，欢迎加入阿里云市场.云璨群咨询(620676291)

### 版本更新

- 20180126 V1.0

### 常见问题

- **上传文件的时候出现`Request Entity Too Large`怎么办**
这个一般会发生在上传大文件的时候，只要进入宝塔面板，点击软件管理中已安装php版本的设置，再点击配置修改，把upload_max_filesize和post_max_size调大，如果问题还存在那么可以排除是php问题，修改站点nginx的配置文件，即进入宝塔面板之后，点击网站，设置，配置文件，在最后一个括号前加入`client_max_body_size 20m;`后面20m大小根据需求修改

#### 云璨，值得信赖的上云专家！
#### 云璨官网http://www.yuncan.com/
