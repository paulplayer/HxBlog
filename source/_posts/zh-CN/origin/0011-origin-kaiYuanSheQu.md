---
title: 开源社区组织模式与决策机制
tags: 
	- Writing
	- Technology
	- Code
	- OpenSource
categories:
	- Origin
date: 2019-06-21 21:08:27
---

{% blockquote ——写在前面，致自己 %}
鹏之徙于南冥也，水击三千里，抟扶摇而上者九万里，去以六月息者也。
{% endblockquote %}

<!-- more -->

## 插图

{% img /gallery/origin/0011-kaiyuanshequ.png 500 开源社区 %}
<p align="center"><b>开源社区</b></p>

-----

# 开源社区组织模式与决策机制特性分析

## 一、开源社区组织模式特性分析
一直以来，传统的组织管理模式分析项目管理问题，设计组织架构，往往采用“自上而下”的思想，所有的元素通过“自上而下”的分层等级关系组织在一起，两个不在同一层级或不在相邻层级的不能直接相互交互。这种模式便于管理、易于实施，仍适用于绝大多数组织。然而，随着互联网的飞速发展，社会中各种不同元素之间的联系日渐增强，在互联网中，没有所谓的控制中心能对所有的信息流动绝对控制，采用传统的“自上而下”的模式对信息的控制和规划，并不总是有效的，也正是这种失效，催生了“自下而上”的组织模式，开源社区便是其中一种。

### 1.开源社区组织模式具有“自下而上”的自组织特性
不同于传统的组织模式，借助于互联网，在软件开发领域出现了一种新的具有“自下而上”特性的组织模式——开源社区模式。这种“自下而上”不仅体现在技术开发上，还体现在社区自治上，具有高度的复杂性和自适应性。开源社区具有自组织的结构逻辑，能够根据周围环境的变化调整自身行为以最大程度的适应环境，可以说，大型开源社区具有互联网环境下的复杂自适应系统的组织特性。复杂系统理论认为，复杂自适应系统能够根据环境以及其他主体行为的变化，不断调整自身行为以适应环境，其内部主体与主体之间、主体与环境之间的通信的流畅程度直接决定复杂自适应系统的发展程度，以复杂自适应系统理论对其来进行剖析，具有较强的理论和现实意义。

### 2.开源社区人员构成具有高度异质性、动态性
大型开源社区是由一群具有不同特性的成员所组成的开发群体，无论是在地理位置、人种、国籍、肤色、意识形态、宗教信仰、文化传统上都有着巨大的差异，还是在学习动机、交流动机、兴趣动机、职业发展动机等参与动机上也不尽相同。不仅如此，开源社区成员的加入和退出也具有高度的动态性，项目研发的参与程度和精力分配，也随着情况的不同表现出高度动态性，可以说，开源社区在人员构成上具有高度的异质性和动态性。

### 3.开源社区项目具有交互复杂、反馈频繁、不断革新、持续演化的特性
大型开源社区开发的项目往往是操作系统、网络平台、Web服务器、编程语言等产品，这些产品技术先进、规模庞大、版本繁多、还存在大量迁移适配工作，开发难度极高，传统的“自上而下”的组织模式投入大量的人力、物力、财力，依旧很难保证项目的成功执行。然而看似低效的“自下而上”的开源社区的组织模式，却吸引了非常多的人员和组织参与研发、维护，由此成员间必须进行复杂的交互，高频的反馈，并以此催化其不断革新功能，持续演化版本等特性。如Linux开源社区,具有持续引入新的创意和技术的机制和能力，使其Linux操作系统产品在技术上保持领先，激发整个开源社区的创造力。

### 4.开源社区生产分配具有任务自我分配、项目成果全员共有的特性
不同于计划分配、按劳分配等传统生产方式，开源社区在任务分配和成果分配上具有任务自我分配、成果全员共享的特性。当大型开源社区发布一个项目的时候，项目协调人会公布项目需求信息，社区内的每个人都可以看到招募信息和条件，申请加入项目。另外，当项目完成后，社区内的每一个成员都可以看到项目源代码，成果是全员共有的，在使用共有成果时要遵守开源软件的许可证，目前，经过OSI（开放源代码促进会）认证的所有开源软件许可证数量共计9大类84种，社区成员按照开源协议进行成果共享。

### 5.开源社区组织方式具有高度开放性和大规模参与性
大型开源社区具有高度开放性和大规模的参与性，一方面，随着时间的发展，一些新的项目和新的程序设计人员不断从外部加入，系统内原有的项目也会因为竞争而优胜劣汰。开源社区极大的汇集了大众的智慧，从这个意义上来说，开源社区也是一个利用集体智慧进行协同创新的平台。系统要素正是在与外界进行信息和能量交换过程中，逐步走向有序。另一方面，也要注意到开源社区90%的工作量由10%的生产者完成，如Sourceforge项目中100项成熟产品的实证研究结果显示，绝大部分项目是由个人完成的，一般情况下也没有超过四个人。因此，规模效应带来的提升往往集中体现在成果的创新性、多样性，而持续性推进和集成工作通常依赖于少数主要生产者。

### 6.开源社区工作方式具有对辅助管理工具的强依赖性
开源社区项目的开发过程中，必须要用到一些辅助工具，其中最重要的就是版本控制系统。另外大型开源社区项目规模庞大，涉及到的人员分布广，构成复杂，沟通管理难度大，开发过程中还需要问题跟踪管理系统、通讯系统、自动化部署和测试系统等各种辅助工具。如Github,Sourceforge.net等主流大型开源社区的工作方式，皆对辅助工具高度依赖。

## 二、开源项目决策机制分析
开源项目由于其组织构成的特殊性和复杂性，社区内部很难一直保证一团和气，毫无争议。事实上，任何一个开源社区项目从出生到成熟的发展历程中，总是充满分歧、矛盾和争端，例如对不同技术路线的评定会触及某些成员的直接利益，不同身份背景和认知的成员在达成共识前经常会有文化和理念冲突，而且这些矛盾和争端不妥善处理，会引起整个社区的震荡甚至分崩离析。因此，即便是开源社区这种分布式的创新模式，也有其内部的治理和协调机制来处理事务，保持社区稳定。
这些规则可以总结为五类，模块化、角色分类、集体决策、能力审查、工具化。模块化指根据项目的复杂程度，大项目可以分成多个模块，进行分工合作；角色分类指的是开源社区内人员角色的权限不同，以及转化机制；决策机制指的是对社区中创造、测试、确认新的代码在社区中的确认机制；能力审查指的是为了保证项目质量和稳定性对参与人的能力审查的机制；工具化是指开源社区提供的各类控制软件进度和质量的流程化管理工具。

### 1.开源社区的治理机制是介于等级制度和完全开放之间的一种中间状态
开源社区作为具有“自下而上”组织特性，其治理机制不同于传统的等级制度下的治理模式，然而其管理也并非完全开放和单纯依靠共识的，而是介于等级制度和完全开放之间的一种分布式权责模式。
一般来说，开源社区治理机制具有“舵手选择”和“民主投票”双重模式，“舵手选择”模式指的是项目的创始者或集成者在技术路线、社区发展等问题的抉择上具有很高的控制权和话语权，“民主投票”模式是指开源社区成员在技术路线、社区发展等问题上也具备民主投票的权利，来避免主观、专断和偏袒。
志愿者可以通过卓越的工作、持续参与的热情来贡献与系统领导者意愿相吻合的技术路线，并通过认证以获取进入核心层的机会，核心层由各子系统的实际控制者组成，系统领导者让渡部分权利给他们，通过他们驾驭整个社群，核心层以外的普通志愿者和用户实际上无法对社群决策产生实质影响，因此开源软件的治理机制具有分布式的特征，并不完全归属于用户创新的范畴。
然而值得注意的是，开源社区这种治理机制主要还是通过社区成员的自觉和合作态度来维护的，奖惩措施往往只是精神道义上的奖惩，以及对违规者代码实行禁入，但其依旧可以自由的获取源代码。

### 2.开源社区的治理机制导致其弱化了用户需求，需要主导机构（或称为中介机构）作为桥梁
虽然开源社区的成果经常以开源软件的形式，向公众提供免费资源并完全开放源代码，具备公用品的部分性质，但受其治理机制的影响，并非完全依赖共同的信仰、价值观，核心层以外的普通志愿者和用户往往权利很小，只拥有Bug处理的投票权利，往往不能对社区决策产生实质影响，虽然一定程度上的影响社区决策，但相比于商业公司，还是极大的弱化了用户需求，因此，为解决实际问题，通常需要主导机构（中介机构）作为桥梁，这也是类似Red Hat这样的商业企业进入开源软件市场、并成功实现行业用户推广的原因之一。

### 3.开源社区的治理机制容易导致“挑战权威”、“功高震主”、“改弦更张”、“用脚投票”等问题
开源社区受其相对松耦合的管理机制的影响，一方面有利于增加社区人员的独立性和多样性，使集体更价睿智；但另一方面，开源社区的治理模式，使得社区用户受声誉等的驱动经常会出现一些取而代之的激励，当其声誉和知识累积超过项目的创始者，即“功高震主”，就会出现“挑战权威”的问题，当被创始者压制后，又随机会“改弦更张”、“自立门户”，而不同技术理念的开发者也经常会“用脚投票”，使得社区人员流失、项目发展受阻。

### 4.主导机构(大型企业、基金会)对开源的影响力越来越大
一般认为，开源社区是将开发者与用户、项目、企业和基金会联系起来的一种相对自由的学习、交流机制，开发者和用户通过社区学习知识、提升技能和知名度、扩展人际圈子，企业通过社区可以提高企业知名度、找到合适的人才、推广技术和产品、降低生产成本。大家相互制约、各取所需，但近年来，随着开源社区的发展壮大，其成长模式不再是原始的以个人兴趣和技术偏好为出发点的“自治”为主的模式，发展模式已经从个人发起、大众参与，逐渐演变成大型企业和基金会倡议成立、主导发展模式，我们称之为主导机构。各社区背后依托的企业和基金会的商业目的和集团利益对社区治理和发展的影响已经越来越明显，企业和基金会扮演的角色对社区的影响力越来越大。以OpenStack开源社区为例，其构成复杂，企业身影众多，涵盖IBM、惠普、华为等底层基础设施供应商，Red Hat和Ubuntu等发布企业商用版本的操作系统厂商，Rackspace等OpenStack发起厂家的主要架构决定者，以及众多用OpenStack构建完整解决方案的企业，各方角色利益交织复杂，企业和基金会对OpenStack开源社区的决策和发展起到决定性作用。
