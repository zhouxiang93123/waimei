---
layout: post
title: "coreboot支持廉价x86服务器主板X11SSH-F"
date: 2020-10-28T07:16:54.000Z
author: Solidot
from: https://www.solidot.org/story?sid=65931
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1603869414000-->
[coreboot支持廉价x86服务器主板X11SSH-F](https://www.solidot.org/story?sid=65931)
------

<div>
<a href="http://https://github.com/hardenedlinux">HardenedLinux</a> 写道 <i>"<a target="_blank" href="https://www.solidot.org/story?sid=57077">x86生态的的封闭性对自由固件社区一直都并不友好</a>，coreboot的发起人之一Ron Minnich在2017年时吐槽过已经有超过10年没有工作站和服务器级别的x86硬件能运行自由固件coreboot了，为了简化适配性于2017年发起的<a href="https://itsfoss.com/linuxboot-uefi/" target="_blank">NERF/LINUXBOOT等项目虽然能快速适配到更多的x86机型</a>上，但当时HardenedLinux社区的<a href="https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/tree/master/docs/hardened_boot">HardenedBoot项目</a>中也发现了此种发发的诸多缺陷，比如主流固件UEFI的DXE模块的重定位问题，而后来的厂商和开源社区的尝试则把启动包含measuredboot实现的载荷推迟到DXE之后，这极大的增加了安全的风险。<a href="https://github.com/hardenedlinux/hardenedlinux_profiles/raw/master/slide/hardening_the_core.pdf">Hardening the COREs</a>支持各种组合的方案，在最高级别的防御方案中HardenedLinux一直都在固件层面<a href="https://www.solidot.org/story?sid=52056" target="_blank">基于coreboot进行打造</a> 。德国的厂商和政府一直都有<a href="https://www.solidot.org/story?sid=62689" target="_blank">支持自由固件的传统</a>，而2019年德国安全厂商9elements正式<a href="https://9esec.io/blog/first-modern-coreboot-server-platform/" target="_blank">开源了Supermicro X11SSH-TF主板的支持</a>，这款支持KabyLake Xeon的服务器打破了常年没有服务器硬件支持coreboot的局面，此后的一年中也收到了一些欧洲用户关于成本方面的反馈，这也是近日HardenedLinux基于X11SSH-TF完成了<a href="https://doc.coreboot.org/mainboard/supermicro/x11-lga1151-series/x11ssh-f/x11ssh-f.html" target="_blank">X11SSH-F的支持</a>的原因之一，用户可以根据自己需求去采购<a href="https://doc.coreboot.org/mainboard/supermicro/x11-lga1151-series/x11ssh-tf/x11ssh-tf.html">X11SSH-TF</a>（~380美金）或者X11SSH-F(~200美金)。"</i><p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
