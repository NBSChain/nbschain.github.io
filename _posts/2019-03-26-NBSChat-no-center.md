---
layout:     post
title:      去中心聊天客户端
subtitle:   操作教程
date:       2019-3-26
author:     
header-img: docs/images/2019/network-protocol-bg.png
catalog: true
tags:
    - NBS Chain
    - 去中心化聊天	
---

# 软件简介
<p class="section-indent">
	这个软件是基于NBS Chain 开发的去中心化聊天客户端，该客户端用于测试NBS Chain的打洞协议（NAT）以及去中心聊天的稳定性。
</p>
<p class="section-indent">
目前该客户端只有window版本；<br>
	支持window10，window7,window8,window vista
</p>
<iframe height=498 width=510 src="http://lxqncdn.miaopai.com/stream/BvmaXK2X49guVi4ehlOjjQ__.mp4" frameborder=0 allowfullscreen></iframe>
## 安装
  * 下载最新客户端安装文件 [前往下载![GitHub release](https://img.shields.io/github/release-pre/NBSChain/ghost-chat.svg?label=last%20release&style=plastic)![GitHub All Releases](https://img.shields.io/github/downloads/NBSChain/ghost-chat/total.svg?logoColor=red&style=plastic)](https://github.com/NBSChain/ghost-chat/releases)

![](https://github.com/NBSChain/nbschain.github.io/blob/master/docs/images/201903/2019-03-26_21-56-40.png?raw=true)  

  * 双击setup.exe安装，安装过程中选择允许防火墙通过。

![安装](https://github.com/NBSChain/nbschain.github.io/blob/master/docs/images/201903/2019-03-26_21-58-06.png?raw=true)
<br>
![防火墙](https://github.com/NBSChain/nbschain.github.io/blob/master/docs/images/201903/2019-03-26_22-01-12.png?raw=true)

## 功能介绍
![界面](https://github.com/NBSChain/nbschain.github.io/blob/master/docs/images/201903/2019-03-26_22-02-24.png?raw=true)
<br>
  - 群聊：通过输入框输入内容回车，即可进行群聊
  - 重启：点击重启按钮可重启NAT
  - 测试：可测试NAT状态，并记录日志
  - 打开：打开日志文件所在目录文件夹（日志文件debug-gossip.txt）
## Bug 反馈渠道
  - 您可以通过邮件将日志文件反馈给NBS开发团队<a href="mailto:nbsadmin@163.com" target="_blank">nbsadmin@163.com</a> 
  - 如果您拥有GitHub账户，也可反馈到项目ISSUSE[![GitHub issues](https://img.shields.io/github/issues/NBSChain/ghost-chat.svg)](https://github.com/NBSChain/ghost-chat/issues)

## 测试计划
<p class="section-indent">
分两个时间段集中测试，各位粉丝根据自己时间选择其中一个时间段参与测试。
</p>
 - 时间段一：3-27（周三）晚 8:00至9:00
 - 时间段二：3-28（周四）上午 8:30至9:30

### 测试操作内容
  - 发送消息【至少5条】
  - 点击测试按钮【至少3次，每次间隔至少5分钟】
  - 重启按钮【如果测试弹出为（如下图） IN：0 ... 则点击重启,建议间隔几分钟】
  - 最后将测试日志发邮件到<a href="mailto:nbsadmin@163.com" target="_blank">nbsadmin@163.com</a>邮箱。 
![防火墙](https://github.com/NBSChain/nbschain.github.io/blob/master/docs/images/201903/2019-03-26_22-54-21.png?raw=true)  
