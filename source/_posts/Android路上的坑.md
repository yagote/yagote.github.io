---
thumbnail: 'https://cdn.jsdelivr.net/gh/yagote/bloIm@master/im/Android.jpg'
title: Android路上的坑
tags: Android studio
categories: Android
date: 2021-07-19 20:48:39
---

---

<!--more-->

+ Android Studio更新后容易出现一些问题啊，特别是gradle 。更新后一直提示gradle扩展不能用，可是gradle扩展明明好好的。本来想卸载gradle后再重新安装一下，卸载掉gradle后，发现问题更大了，这Android Studio 干脆不能打开了，一顿操作猛如虎，最后百度了一下才解决了这个问题，还是的安装好gradle才可以打开。没有把错误截图下来，忘了具体的错误内容了。反正就感觉不太好下手弄

+ 发现Android Studio中gradle的问题是真的多，是不是就搞出一个错误，大多都是和gradle相关。

+ 打开Android studio导入项目还会提示failed at (这是导入的时间)，第一次上手，也不知道是什么原因，也没提示到底是什么错误，就在运行结果显示栏左边有failed at

+ 创建一个空活动时，不能自动生成.java 文件和一个叫什么来着的文件。第一次创建空活动时就能自动生成这两个文件，之后忘了修改了什么就再也不能生成这两个文件了。好像是加载了 不同版本的gradle……忘了

+ 好多坑，这才刚刚开始……

