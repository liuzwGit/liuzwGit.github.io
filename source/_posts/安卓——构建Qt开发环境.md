---
title: 安卓——构建Qt开发环境
date: 2021-07-25 19:26:17
categories: "安卓" #分类
tags: #标签
	- android
	- env
	- app
---

&emsp;&emsp;Qt->工具->选项中可以配制android的开发环境，其中，JDK可以通过百度搜索JAVA JDK进行下载，Openssl可以直接点击链接图标进行下载，但是andorid提供的地址下载构建起来比较麻烦，而且，容易出错。

&emsp;&emsp;比较简单的办法是，百度andriod studio官网，下载android studio，然后，进行安装。安装时会指定下载android sdk，如下图所示。

![AndroidStudio设置SDK路径](AndroidStudio设置SDK路径.png)

![AndroidStudio确认SDK信息](AndroidStudio确认SDK信息.png)

![AndroidStudio点击完成开始下载](AndroidStudio点击完成开始下载.png)

&emsp;&emsp;安装完成后，设置Qt->工具->选项中的andorid sdk路径，设置后会提示必要的软件不全，需要更新，依次点击accpet，如下图所示。

![Qt接受更新AndroidStudioSDK](Qt接受更新AndroidStudioSDK.png)

![Qt更新AndroidStudioSDK中](Qt更新AndroidStudioSDK中.png)

![Qt更新AndroidStudioSDK完成](Qt更新AndroidStudioSDK完成.png)

&emsp;&emsp;自动下载更新后，Qt即可使用android开发环境。

![安卓中运行QT程序](安卓中运行QT程序.png)