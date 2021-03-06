---
layout: post
title:  "数据混淆"
date:   2019-12-27 14:23:49 +0500
---
APT可能会混淆命令和控制流量，从而使其更难检测。隐藏了命令和
控制（C2）通信（但不一定加密），以使内容更难以发现或解密，
并使通信不那么显眼并隐藏命令。这包括许多方法，例如使用隐写术
或模拟合法协议将垃圾数据添加到协议流量。
😁🤣
{% highlight ruby %}

对手可能会混淆命令和控制流量，从而使其更难检测。隐藏了命令和
控制（C2）通信（但不一定加密），以使内容更难以发现或解密，并
使通信不那么显眼并隐藏命令。这包括许多方法，例如使用隐写术或
模拟合法协议将垃圾数据添加到协议流量。
1)	垃圾数据
对手可能会将垃圾数据添加到用于命令和控制的协议中，从而使检测
更加困难。通过将随机或无意义的数据添加到用于命令和控制的协议
中，对手可以防止采用琐碎的方法来解码，解密或以其他方式分析流
量。示例可能包括使用垃圾字符附加/前置数据或在有效字符之间写
入垃圾字符。
2)	隐写术
对手可能会使用隐写术技术来隐藏命令和控制流量，从而使检测工作
更加困难。隐写技术可用于隐藏系统之间传输的数字消息中的数据。
此隐藏信息可用于命令和控制受感染的系统。在某些情况下，使用隐
写术嵌入的文件（例如图像或文档文件）的传递可用于命令和控制。
3)	协议模拟
对手可能冒充合法协议或Web服务流量，以掩盖命令和控制活动并阻
碍分析工作。通过模拟合法协议或Web服务，攻击者可以使他们的命
令和控制流量与合法网络流量融合在一起。

攻击者可能冒充伪造的SSL / TLS握手，以使后续流量看起来像是SSL / TLS加密的，有可能干扰某些安全工具，或者使流量看起来像与受信任
实体有关。

