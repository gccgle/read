---
layout: post
title: "理工男的动手能力不可荒废-NAS篇"
author: al
categories: [ 技巧, 硬件 ]
image: assets/images/nas.jpg
tags: [群晖]
excerpt: "入手群晖920+，折腾几日，已实现NAS的一些基本功能。资料储存备份，不同设备间的共享，用起来“纵享丝滑”。想起在原单位，设计部的同事们隔三岔五都要申请加购一个移动硬盘；一个笨且低效的方法行之经年，无人提议主张来点改变，这里既可能因大家对新事物缺乏好奇了解，也有公司管理机制的疏漏。"
---



入手群晖920+，折腾几日，已实现NAS的一些基本功能。资料储存备份，不同设备间的共享，用起来“纵享丝滑”。想起在原单位，设计部的同事们隔三岔五都要申请加购一个移动硬盘；一个笨且低效的方法行之经年，无人提议主张来点改变，这里既可能因大家对新事物缺乏好奇了解，也有公司管理机制的疏漏。

## 1.
基本的，把个人资料全部上载到这个私有云里，配合对应的客户端让电脑、手机随时访问。四盘位的920+，买了两块8T的酷狼硬盘，使用了群晖自有的SHR组盘模式，实际可用空间从两个盘的16T直接减半成8T，着实肉疼。只能安慰自己，把这8T的空间用真正重要的资料装满，应是猴年马月之后的事儿了。

家里原有一块的2T的硬盘做了一个独立的存储池，因为容量、转数不一致，就没有把它和两块新买的组在一起，当作纯粹的影音资源储存盘。

## 2.
客厅的华为智慧屏，居然不能直接链接局域网资源，这智慧有点名不副实。好在有曲线救国的方式。测试了Es文件浏览器，发现无法播放视频，弃。随即看到了Kodi，官网上下载了最新版本，使用U盘顺利安装，并分别测试使用smb、ftp等协议装载模式，效果良好（前人有提及的闪退问题，在我安装的Kodi v19.1 (Matrix)版本上，应该已被修复）。大赞Kodi的界面UI，精致耐看。不像国内多数应用，让人吐槽无力。但尝试安装Emby插件，用来做信息刮削和资源管理，无功而返，悻悻然，回到最简单的文件列表样式。

## 3.
NAS功能是强大的，奈何需要一定的精力去折腾。尤其一些技术性的概念、手段颇为陌生，需要深入研究并结合动手才能理解个一星半点。入手一周，还有许多未竟事宜，包括但不限于：内网穿透，设置域名，影音资源的刮削，链路聚合、虚拟机等等。

## 4.
就以上这些最最基础的功能来说，现实中它们都分别有替代手段来实现。但部署NAS带来的诸多便利，又真切的不容抹杀。根本上，解决的依然是一个焦虑问题，因这些分散在各设备上的资料得不到应有的保管、整理和复用而焦虑。
