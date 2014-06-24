---
layout: post
title: "first_bolg 解决自建blog打开很慢的问题"
date: 2014-06-24 11:33:46 +0800
comments: true
categories: 
---


刚刚搭建的github博客，换了一个主题，发现发开很慢，是因为主题的一个sass文件使用了google字体，最近google被墙的很严重，导致加载很慢，找到那个scss文件（直接在blog本地文件夹搜索google）找到`fonts.googleapis.com` 替换成把 google的域名替换成360在国内的镜像就 `fonts.useso.com` 可以了。

![如图](/images/heroBack.jpg)

懒得写那么多。直接看别人写好的 [如何替换](http://blog.sina.com.cn/s/blog_627508a20101ivpg.html "点开链接") .
