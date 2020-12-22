---
layout: post
title: "Chrome 的新缓存分区系统影响 Google Fonts 性能"
date: 2020-12-07T14:25:47.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66299
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1607351147000-->
[Chrome 的新缓存分区系统影响 Google Fonts 性能](https://www.solidot.org/story?sid=66299)
------

<div>
10 月份释出的 Chrome 86 改变了缓存系统，引入了缓存分区去储存不同网站的缓存，防止利用缓存共享资源的攻击方法。但新的缓存系统影响到了设计使用缓存的 Web 服务如 Google Fonts。Google Fonts 被数百万网站广泛使用，它允许网站使用一行代码加载托管在  Google 服务器里的任意字体。当字体下载到缓存之后，用户无需访问每个网站重新下载一遍字体。但新的缓存分区系统事实上<a href="https://wicki.io/posts/2020-11-goodbye-google-fonts/" target="_blank">让 Google Fonts 变得无用</a>，因为新系统强迫用户访问一个网站后需要重新下载一遍字体，网站在自己的服务器上托管字体将比 Google 托管更高效。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
