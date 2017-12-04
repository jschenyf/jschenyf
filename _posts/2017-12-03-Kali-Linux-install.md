---
layout: post
title: Kali Linux 系统的安装
date: 2017-12-3 
tags: Kali-Linux   
---

### 介绍
Kali linux 是基于Debian的Linux再发行版，前身是BackTrack Linux，系统里面预装了许多渗透测试软件，包括nmap，burpsuite，Aircrack-ng,Wireshark等，据统计目前大概共14大类600多种工具，这些工具主要用于渗透测试以及安全审计。  
![Tool-type](\images\posts\Kali\Tool-type.png)  
关于Kali Linux 里相关工具的使用方法，可以参考[Kali Linux 工具使用中文说明书](https://www.hackfun.org/kali-tools/kali-tools-zh.html)，里面几乎包含了所有工具的详细说明及使用示例。　　

### 下载 Kali linux 
Kali Linux的下载可以访问[官方下载链接](https://www.kali.org/downloads/)下载你需要的最新的系统版本，有的时候你想要获取其它小版本，可以访问[历史版本](http://cdimage.kali.org/)链接去进行选择下载。  
镜像下载完之后需要使用工具去校验镜像的哈希值，以确保镜像的完整性，防止因镜像问题，在后续的过程中影响系统使用的稳定性。在这里推荐使用[cmder](http://cmder.net/),它是Windows上的一款功能强大的终端模拟器，里面包含了许多小工具，而且使用十分方便，只需下载解压之后，直接双击运行程序即可。  
在shell窗口里运行相关的命令，计算出镜像对应的哈希值，计算时间与文件的大小有关，因为镜像文件大概有2G左右的大小，所以要稍微等一段时间。
![cmder](\images\posts\Kali\cmder.png)  
将计算出来的结果与官网上提供的sha256sum值进行比对，可以看到数值一致，确定镜像下载完整。　　
```
49b1c5769b909220060dc4c0e11ae09d97a270a80d259e05773101df62e11e9d
```

### 系统安装






