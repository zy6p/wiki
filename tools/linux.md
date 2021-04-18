---
title: linux高效开发
description: 
published: true
date: 2021-04-18T02:18:31.565Z
tags: 
editor: markdown
dateCreated: 2021-04-16T05:48:05.036Z
---

# Why Linux

Linux 是一种自由和开放源码的类UNIX操作系统。

## 竞品

与 Linux 对比的应该是 Windows、Mac 这些操作系统，它只是一个操作系统。    

比如有同学可能用过 linux 虚拟机，那与之对比的应该是同样配置的 win 虚拟机。

## 为什么

**效率**    

### 案例

* 传文件
    在 win 上绝大多数软件都是 Gui 图形界面，比如想让 win 复制一个文件到另一处，就需打开文件资源管理器，那如果想把文件复制到远程服务器上，就只能借助软件了。同样的操作在 Linux 上只需要几行脚本，轻松完成。
    但在 win 上互相传文件绝大多数是用 QQ，但 linux 上 QQ 体验较差，这是一大弊端。
* 配置环境
    比如配置 C++ 开发环境，在 win 上是几乎不可能完成的事情，比如配置 GDAL 库，体验非常痛苦。但在 Linux 下有强大的包管理，只需要一行代码非常轻松。
    再如配置 Python 开发环境，在 win 上都会选择 anaconda，确实能解决不少问题。但 cmd、文件编码都是 gbk 码，很容易造成读写文件失败，比如 QGIS 的 GDAL 算法都用不了。
    但 matlab 是跨平台的，两种体验一致。
* 版权
    linux 上有超多开源免费软件，工具很多，GitHub资源丰富。

### 缺点

国外总结：[英文版](http://itvision.altervista.org/why.linux.is.not.ready.for.the.desktop.current.html)，[中文版](https://www.oschina.net/translate/why-linux-is-not-ready-for-the-desktop-current)(2013版，现不是很适用)

* 国内软件支持很差。
    比如 qq、微信、腾讯会议、微信开发者工具、qq音乐、网易云、百度网盘等。一般都有 wine 版，但体验一般。
    国内常用软件支持 linux 的可能就只有 wps 了。
* 专业软件支持很差。
    比如 GIS 的 arcgis，遥感的 ENVI、ERDAS 等。
* 驱动支持稍差。
    比如 wifi 网卡，少部分需要自己安装驱动。

### 怎么选

小孩子才做选择。    

- 如果你用电脑主要是用于开发，那可以选 linux。
- 如果你现在严重依赖 qq、arcgis、envi，那可以体验一下虚拟机。
- 如果你的笔记本很耗电，那可以选 linux。






