---
layout: wiki
title: 定制小程序操作
categories: 小程序
description: 第三方定制小程序添加、升级等相关操作
keywords: 小程序
---

**目录**

* TOC
{:toc}
## 添加定制

#### 联系设计出图

#### [七牛]( https://portal.qiniu.com/signin?redirect=%2Fcreate )上传图片

1. 控制台里点击上传文件，如下图。

![图1](https://raw.githubusercontent.com/ylq1994/PicBed/master/daily/qiniuResource.png)

2. 在下图1的地方写上对应的路径[^路径],然后点击上传图片，图片统一名字为：
   * logo：http://img1.eeeff.com/+对应路径+logo.png
   * 登录页背景图：http://img1.eeeff.com/+对应路径+indeximg.png
   * 首页背景图：http://img1.eeeff.com/+对应路径+indeximg.png
   * 分享展示图片：http://img1.eeeff.com/+对应路径+sharePic.png

![](https://raw.githubusercontent.com/ylq1994/PicBed/master/daily/qiniuUploadImage.png)

#### 提交

[提交定制]( http://122.114.19.234:5566/Home/AddDZ ),根据页面提示，点击提交，成功后会生成授权二维码，发给客服让客户扫描即可，然后在[列表页]()



## 定制操作

#### 提交定制小程序代码

1. 微信开发者工具中将测试无误的代码提交上传.

2. 上传完成后，登录[微信开放平台]( https://open.weixin.qq.com/cgi-bin/applist?t=manage/list&page=0&num=20&openapptype=2048&token=c2297d863c0c2093588c1012e2f5461bf2ce9cf2&lang=zh_CN )，如下图：

   ![](https://raw.githubusercontent.com/ylq1994/PicBed/master/daily/wxKaiFangPingTai1.jpg)

   ![](https://raw.githubusercontent.com/ylq1994/PicBed/master/daily/wxKaiFangPingTai2.jpg)

   ![](https://raw.githubusercontent.com/ylq1994/PicBed/master/daily/wxKaiFangPingTai3.jpg)

   将提交到草稿箱的小程序添加到模板库后，在[后台]( http://122.114.19.234:5566/Home/Listviewdz)更新最新的模板id和版本号信息。![](https://raw.githubusercontent.com/ylq1994/PicBed/master/daily/wxKaiFangPingTai4.jpg)，然后再执行小程序版本更新的操作，否则提交审核的还是旧版本，==切记，先更新这里的版本信息，然后再执行升级操作==。

####  客户小程序提交

在[操作页]( http://122.114.19.234:5566/Home/Listviewdz )根据提示可以去完成相应操作，目前有的操作有：

* 更新定制小程序。
* 添加小程序插件
* 查看审核状态
* 更新后台记录模板id和版本id





---

[^路径]: 易房大师：image/dingzhi/yfds-公司id/  房客多：image/dingzhi/fkd-城市id/