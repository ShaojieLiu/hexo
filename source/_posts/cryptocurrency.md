---
title: 加密电子货币的原理
date: 2019-03-25 19:53:32
tags: crypto
---

# Reference

[参考视频](https://v.youku.com/v_show/id_XMzY3MjIzMTczMg==.html?spm=a2hzp.8244740.0.0)

# 引子

> 什么是矿工呢?
> 他们并非不停地挖矿, 而是使用区块内的所有字符串作为输入(包括它所猜的数字)进行 SHA256 计算, 当结果符合一定条件时(例如开头是 30 个零), 即为成功. 你现在一定有很多疑问, 区块内包含了什么, 他为什么要猜数字, 为什么要不停地进行 hash 计算? 今天的文章或许可以为你带来解答.

![矿工挖矿](miner1.png)

# 从分布式账本说起

假如你和你的三个朋友有频繁的金钱往来, 为了避免现金实时结算带来烦恼, 你们会拥有一个账本来记录一切未结算的金钱往来.
![独立账本](ledger.png)