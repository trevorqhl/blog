---
layout: post
title:  "How to install Centos 8 from internet"
date:   2020-04-21 08:30:52 -0400
img: linux.jpeg
categories: Linux
tags: OS
---

![Linux]({{site.baseurl}}/images/linux.jpeg)

1. Download the minimal iso from a [Centos Mirror][centos-iso]

2. If using windows, download [Rufus][Rufus] and install it to Windows

3. Burn the iso into a USB drive

4. Boot your computer using the USB drive

5. From Installation Source
```
Select On the network and use 
http://
Enter URL 
mirror.centos.org/centos/8/BaseOS/x86_64/os/
```
6. The rest are customized to your preference and kick off installation

[centos-iso]: http://mirror.csclub.uwaterloo.ca/centos/8.1.1911/isos/x86_64/
[Rufus]: https://rufus.ie/
