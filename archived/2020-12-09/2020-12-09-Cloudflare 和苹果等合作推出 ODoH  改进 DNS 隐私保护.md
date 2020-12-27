---
layout: post
title: "Cloudflare 和苹果等合作推出 ODoH  改进 DNS 隐私保护"
date: 2020-12-09T10:31:04.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66319
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1607509864000-->
[Cloudflare 和苹果等合作推出 ODoH  改进 DNS 隐私保护](https://www.solidot.org/story?sid=66319)
------

<div>
传统的 DNS 查询是明文的，其隐私问题越来越引起关注。为了保护用户隐私 IETF 标准化了两种协议 DNS over HTTPS (DoH) 和 DNS over TLS (DoT)去加密 DNS。Firefox 等已经加入了对 DoH 的支持，而云服务商 Cloudflare 是一个主要的公共 DoH/DoT 服务商。但 DoH/DoT 的推出也引发了两个问题，其一是 DNS 的中心化引入了单点故障，其二是解析器仍然可以将所有查询关联到客户 IP 地址。为了更好的保护用户隐私，Cloudflare、Fastly 和苹果的工程师<a href="https://blog.cloudflare.com/oblivious-dns/" target="_blank">合作开发了新的协议 ODoH（</a>代表 Oblivious DNS over HTTPS）。ODoH 加入了一个公钥加密层以及客户端和 DoH 服务器之间的网络代理，确保只有用户才能访问 DNS 信息及其 IP 地址。工程师们用 Rust、Go 等语言实现了互操作 ODoH 实现并将其开源，Cloudflare 的公共 DNS 服务器 1.1.1.1 已经能支持 ODoH 查询。Firefox 已经表达了支持 ODoH 的意愿。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
