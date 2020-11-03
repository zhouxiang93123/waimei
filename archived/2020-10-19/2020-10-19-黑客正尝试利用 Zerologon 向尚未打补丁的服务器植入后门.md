---
layout: post
title: "黑客正尝试利用 Zerologon 向尚未打补丁的服务器植入后门"
date: 2020-10-19T09:33:45.000Z
author: Solidot
from: https://www.solidot.org/story?sid=65846
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1603100025000-->
[黑客正尝试利用 Zerologon 向尚未打补丁的服务器植入后门](https://www.solidot.org/story?sid=65846)
------

<div>
微软在 8 月的例行更新中修复了被命名为 Zerologon 的高危漏洞 CVE-2020-1472，它允许已在目标网络立足的任意攻击者完全控制 Active Directory。该漏洞可被用于发动勒索软件攻击或植入间谍软件。安全研究人员在 9 月中旬<a href="https://www.solidot.org/story?sid=65546">公开了</a>漏洞利用的 poc 代码，之后<a href="https://www.solidot.org/story?sid=65654">就传出</a>黑客正在利用该漏洞的消息。安全研究员 Kevin Beaumont 上周<a href="https://arstechnica.com/information-technology/2020/10/hackers-are-using-a-severe-windows-bug-to-backdoor-unpatched-servers/">披露</a>，他设立的蜜罐探测到黑客正尝试利用 Zerologon 向尚未打补丁的服务器植入后门。攻击是利用脚本发动的，所有命令都在数秒内完成，攻击者使用用户名 sdb 和密码 jinglebell110@ 创建了账号并启用了远程桌面，即使服务器后来打上了补丁攻击者仍然能持续远程访问。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
