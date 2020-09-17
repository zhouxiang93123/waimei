---
layout: post
title: "黑客正在利用一个 WordPress 插件高危漏洞"
date: 2020-09-02T07:49:34.000Z
author: Solidot
from: https://www.solidot.org/story?sid=65420
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1599032974000-->
[黑客正在利用一个 WordPress 插件高危漏洞](https://www.solidot.org/story?sid=65420)
------

<div>
黑客<a href="https://arstechnica.com/information-technology/2020/09/hackers-are-exploiting-a-critical-flaw-affecting-350000-wordpress-sites/">正在利用</a> WordPress 插件 <a href="https://wordpress.org/plugins/wp-file-manager/">File Manager</a> 的一个漏洞在网站上执行命令和恶意脚本。File Manager 的安装量超过 70 万，用于操作本地和服务器上的文件。泰国安全公司 NinTechNet 最早报告了黑客正在利用漏洞上传名叫 hardfork.php 的脚本，然后用它向 WordPress 脚本 /wp-admin/admin-ajax.php 和 /wp-includes/user.php 注入代码。另一家安全公司 Wordfence 称，过去几天它屏蔽了 45 万次漏洞利用尝试，攻击者尝试注入不同类型的文件，部分文件是空的，可能是为了侦察网站是否存在漏洞，然后再注入恶意文件。上传的文件名字有 hardfork.php、hardfind.php 和 x.php。统计显示，70 多万安装的 File Manager 中有 52% 存在漏洞。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
