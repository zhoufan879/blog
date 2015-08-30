---
layout: post
title: "Hello world"
description: ""
category: 
tags: []
---
{% include JB/setup %}

## 第一次使用 Jekyll

其实是第二次用了，第一次是昨天；编译了一天的文件，始终报错（UTF-8格式不正常 Liquid Exception: invalid byte sequence in UTF-8）  T^T

后来按网上高手的经验，去jekyll目录找到convertible.rb文件分析错才知道原因：
原本文件用VIM编辑，保存编码格式为默认（ANI神马的），恰好文本里又有这样那样的中文。

## 最后，还是感谢 Jekyll 给我带来的痛苦体验！！！

希望将来可以伴随我“茁壮”成长