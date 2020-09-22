---
layout: post
title: "Linux 内核支持 Rust 开发所面临的挑战"
date: 2020-09-07T09:16:28.000Z
author: Solidot
from: https://www.solidot.org/story?sid=65463
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1599470188000-->
[Linux 内核支持 Rust 开发所面临的挑战](https://www.solidot.org/story?sid=65463)
------

<div>
作为一种现代系统级语言，Rust 比 C 或 C++ 更安全也更容易使用，Linux 内核主要是用 C 开发的，Rust 被很多人认为是 C 和 C++ 的最佳替代，而 Linus Torvalds 等内核的核心维护者对在内核中使用 Rust <a href="https://www.solidot.org/story?sid=64946">持开放态度</a>。为了用于内核开发，Rust 只是能生成可链接到内核的代码是远远不够的，需要找到一种方法让 Rust 能访问内核使用的 API，而内核所有的 API 都定义在 C 头文件内。 Rust 支持与 C 代码的互操作，包括调用使用 C ABI 的函数。表面看，Rust 能很好的与现有的  C API 整合起来，但魔鬼在细节中。在最近举行的虚拟 <a href="https://linuxplumbersconf.org/">Linux Plumbers Conference</a> 会议上，开发者谈论了内核使用 Rust 开发<a href="https://lwn.net/SubscriberLink/829858/281103f9c6fd0dc2/">所面临的挑战</a>。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
