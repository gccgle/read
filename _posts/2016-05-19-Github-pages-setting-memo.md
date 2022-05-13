---
layout: post
title: "Github Pages配置备忘"
author: al

categories: HOW
excerpt: "一些个人配置Github Pages的过程备忘，从Git使用、Ruby等环境部署、到一些不可避免的报错，甚至是Markdown等语言基础等，都无比陌生。是以将一些参考信息加以汇聚整理。"

---


## 参考资料
- 在Windows上安装Jekyll：<https://www.jianshu.com/p/58e2c5ea3103>
- 下载RubyInstallers:<https://rubyinstaller.org/downloads/>
- Windows命令行cmd之cd命令用法:<https://blog.csdn.net/zdy219727/article/details/98605287>
- Github+Jekyll搭建个人博客:<https://blog.csdn.net/White_Idiot/article/details/69397224>
- jekyll模板：<http://jekyllthemes.org/>
- GitHub和Git超详细使用教程: <https://blog.csdn.net/buknow/article/details/80325986>


## 环境部署注意事项
- 安装Ruby时，避免安装在文件名含有空格的文件夹内，如Program Files。  
- 要安装MSYS2 and MINGW development toolchain  
- 拉取gmail.com时报错。解决方案：翻墙  


## 各种报错的解决
安装jekyll时报错：
> error installing jekyll  
> failed to build gem native extension  

解决:下载rubyinstaller-devkit版本安装。

> $ git push origin master  
> fatal: unable to access 'https://github.com/gccgle/readunread.cn/': Failed to connect to github.com port 443: Timed out

解决参阅：<https://blog.csdn.net/csvdvg/article/details/62444144>

## Git使用
当$变为>时，CTRL+D可以退回



