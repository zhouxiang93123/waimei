---
layout: post
title: "Chrome on Android 支持 DNS-over-HTTPS (DoH)"
date: 2020-09-03T10:57:01.000Z
author: Solidot
from: https://www.solidot.org/story?sid=65437
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1599130621000-->
[Chrome on Android 支持 DNS-over-HTTPS (DoH)](https://www.solidot.org/story?sid=65437)
------

<div>
Google 官方博客 <a href="https://blog.chromium.org/2020/09/a-safer-and-more-private-browsing.html" target="_blank">宣布</a> Chrome for Android 将支持 DNS-over-HTTPS(DoH)。DoH 设计通过 HTTPS 加密向第三方或用户自己搭建的 DNS 服务器发出域名查询请求，这种方法被认为相对于明文连接 DNS 服务器更安全。Chrome 的桌面版本从 5 月发布的 v83 起就加入了对 DoH 的支持，但该功能并未加入到 Android 和 iOS 版本中。Google 现在宣布 Chrome for Android 85 将逐步启用该功能，浏览器的设置内引入了 Secure DNS 的新选项，启用之后 Chrome 将会尝试通过 DoH 发出加密的域名查询请求，如果不支持则回滚到明文请求。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
