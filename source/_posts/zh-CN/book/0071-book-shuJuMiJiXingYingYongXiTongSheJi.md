---
title: 《数据密集型应用系统设计》
tags:
	- Reading
    - Business
    - Economy
    - Management
categories:
	- Read
date: 2022-08-16 18:19:16
---

{% blockquote —— Alan Kay, Dr.Bobb 2012 %}
计算是一种流行文化，流行文化鄙视历史。流行文化关乎个体身份和参与感，但与合作无关。流行文化活在当下，也与过去和未来无关。
{% endblockquote %}
<!-- more -->

## 插图
{% img /gallery/book/0071-shujumijixingyingyong.jpg 500 数据密集型应用系统设计 %}
<p align="center"><b>数据密集型应用系统设计</b></p>

-----

# 《数据密集型应用系统设计》

这几乎是数据行业里面的一本技术神书，豆瓣评分9.6分，书中很多原理讲的都很深很透，又很容易理解，系统性的帮自己穿起来了散落的各种数据相关的碎片知识。适合在工作时，当作一本工具书，随时的翻开，参考前人经验。

现今，尤其是在互联网领域，大多数应用都属于数据密集型应用。本书从底层数据结构到顶层架构设计，将数据系统设计中的精髓娓娓道来。其中的宝贵经验无论是对架构师、DBA、还是后端工程师、甚至产品经理都会有帮助。

本书旨在帮助大家更好的驾驭处理数据和存储数据的相关技术，它不针对某一个特定软件，也不是纯理论习题。而是通过深入探讨一些成功的数据系统案例，梳理其核心算法，探讨其设计理念和背后的权衡知道，在此过程中，做到“知其然，知其所以然”。全书分为三大部分：

第一部分，主要讨论有关增强数据密集型应用系统所需的若干基本原则。首先开篇第1章即瞄准目标：可靠性、可扩展性与可维护性，如何认识这些问题以及如何达成目标。第2章我们比较了多种不同的数据模型和查询语言，讨论各自的适用场景。接下来第3章主要针对存储引擎，即数据库是如何安排磁盘结构从而提高检索效率。第4章转向数据编码（序列化）方面，包括常见模式的演化历程。

第二部分，我们将从单机的数据存储转向跨机器的分布式系统，这是扩展性的重要一步，但随之而来的是各种挑战。所以将依次讨论数据远程复制（第5章）、数据分区（第6章）以及事务（第7章）。接下来的第8章包括分布式系统的更多细节，以及分布式环境如何达成一致性与共识（第9章）。

第三部分，主要针对产生派生数据的系统，所谓派生数据主要指在异构系统中，如果无法用一个数据源来解决所有问题，那么一种自然的方式就是集成多个不同的数据库、缓存模块以及索引模块等。首先第10章以批处理开始来处理派生数据，紧接着第11章采用流式处理。第12章总结之前介绍的多种技术，并分析讨论未来构建可靠、可扩展和可维护应用系统可能的新方向或方法。

《数据密集型应用系统设计》[图书链接](https://item.jd.com/12437624.html)