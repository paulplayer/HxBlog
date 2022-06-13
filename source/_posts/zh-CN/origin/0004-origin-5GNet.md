---
title: 5G 网络相关
tags: 
	- Writing
	- Theoretical
	- Network
	- Hightech
categories:
	- Origin
date: 2017-12-27 15:08:27
---

{% blockquote ——写在前面，致自己 %}
学贵有恒，何必三更眠五更起，最无益只怕一日曝十日寒。
{% endblockquote %}

<!-- more -->

## 插图

{% img /gallery/origin/0004-5G.jpg 500 5G Logo %}
<p align="center"><b>5G Logo</b></p>

-----

# 学习笔记:5G网络相关

> 原文链接 5G[百度百科](https://baike.baidu.com/item/5G/29780?fr=aladdin)

## 5G 相关知识

第五代移动电话行动通信标准，也称第五代移动通信技术，外语缩写：5G。也是4G之后的延伸，正在研究中，5G网络的理论下行速度为10Gb/s（相当于下载速度1.25GB/s）。

2017年12月21日，在国际电信标准组织3GPP RAN第78次全体会议上，5G NR首发版本正式冻结并发布。

### 超密集异构网络

未来 5G 网络正朝着网络多元化、 宽带化、 综合化、 智能化的方向发展。随着各种智能终端的普及，面向 2020 年及以后，移动数据流量将呈现爆炸式增长。在未来 5G 网络中， 减小小区半径， 增加低功率节点数量，是保证未来 5G 网络支持 1 000 倍流量增长的核心技术之一 。因此， 超密集异构网络成为未来 5G 网络提高数据流量的关键技术。

未来无线网络将部署超过现有站点 10 倍以上的各种无线节点，在宏站覆盖区内，站点间距离将保持 10 m 以内，并且支持在每 1 km2 范围内为 25 000个用户提供服务 。同时也可能出现活跃用户数和站点数的比例达到 1∶ 1的现象， 即用户与服务节点一一对应。密集部署的网络拉近了终端与节点间的距离，使得网络的功率和频谱效率大幅度提高，同时也扩大了网络覆盖范围，扩展了系统容量，并且增强了业务在不同接入技术和各覆盖层次间的灵活性。虽然超密集异构网络架构在 5G 中有很大的发展前景，但是节点间距离的减少，越发密集的网络部署将使得网络拓扑更加复杂， 从而容易出现与现有移动通信系统不兼容的问题。在 5G 移动通信网络中，干扰是一个必须解决的问题。网络中的干扰主要有:同频干扰， 共享频谱资源干扰， 不同覆盖层次间的干扰等。现有通信系统的干扰协调算法只能解决单个干扰源问题， 而在 5G 网络中，相邻节点的传输损耗一般差别不大，这将导致多个干扰源强度相近，进一步恶化网络性能，使得现有协调算法难以应对。此外， 由于业务和用户对 QoS需求的差异性很大，5G 网络需要采用一些列措施来保障系 统 性 能， 主 要 有: 不同业务在网络中的实现，各种节点间的协调方案，网络的选择 ， 以及节能配置方法等。

准确有效地感知相邻节点是实现大规模节点协作的前提条件。在超密集网络中， 密集地部署使得小区边界数量剧增，加之形状的不规则，导致频繁复杂的切换。为了满足移动性需求， 势必出现新的切换算法;另外， 网络动态部署技术也是研究的重点。由于用户部署的大量节点的开启和关闭具有突发性和随机性， 使得网络拓扑和干扰具有大范围动态变化特性;而各小站中较少的服务用户数也容易导致业务的空间和时间分布出现剧烈的动态变化。

### 自组织网络

传统移动通信网络中， 主要依靠人工方式完成网络部署及运维，既耗费大量人力资源又增加运行成本，而且网络优化也不理想。在未来 5G 网络中，将面临网络的部署、 运营及维护的挑战， 这主要是由于网络存在各种无线接入技术， 且网络节点覆盖能力各不相同，它们之间的关系错综复杂。因此，自组织网络(self-organizing network， SON) 的智能化将成为 5G 网络必不可少的一项关键技术。

自组织网络技术解决的关键问题主要有以下 2点:①网络部署阶段的自规划和自配;②网络维护阶段的自优化和自愈合。自配置即新增网络节点的配置可实现即插即用，具有低成本、 安装简易等优点。自优化的目的是减少业务工作量， 达到提升网络质量及性能的效果， 其方法是通过 UE 和eNB 测量，在本地 eNB 或网络管理方面进行参数自优化。自愈合指系统能自动检测问题、 定位问题和排除故障，大大减少维护成本并避免对网络质量和用户体验的影响。自规划的目的是动态进行网络规划并执行，同时满足系统的容量扩展、 业务监测或优化结果等方面的需求。目前，主要有集中式、 分布式以及混合式 3 种自组织网络架构。其中， 基于网管系统实现的集中式架构具有控制范围广、 冲突小等优点，但也存在着运行速度慢、 算法复杂度高等方面的不足;而分布式恰恰相反， 主要通过 SON 分布在eNB 上来实现， 效率和响应速度高， 网络扩展性较好，对系统依懒性小， 缺点是协调困难;混合式结合集中式和分布式 2 种架构的优点，缺点是设计复杂。SON 技术应用于移动通信网络时， 其优势体现在网络效率和维护方面， 同时减少了运营商的资本性支出和运营成本投入。由于现有的 SON 技术都是从各自网络的角度出发， 自部署、 自配置、 自优化和自愈合等操作具有独立性和封闭性， 在多网络之间缺乏协作。因此，研究支持异构网络协作的 SON 技术具有深远意义

### 内容分发网络

在未来 5G 中， 面向大规模用户的音频、 视频、图像等业务急剧增长， 网络流量的爆炸式增长会极大地影响用户访问互联网的服务质量 。如何有效地分发大流量的业务内容， 降低用户获取信息的时延，成为网络运营商和内容提供商面临的一大难题。仅仅依靠增加带宽并不能解决问题， 它还受到传输中路由阻塞和延迟、 网站服务器的处理能力等因素的影响，这些问题的出现与用户服务器之间的距离有密切关系。内容分发网络 (content distribution network， CDN) 会对未来 5G 网络的容量与用户访问具有重要的支撑作用。

内容分发网络是在传统网络中添加新的层次，即智能虚拟网络。CDN 系统综合考虑各节点连接状态、 负载情况以及用户距离等信息，通过将相关内容分发至靠近用户的 CDN 代理服务器上， 实现用户就近获取所需的信息，使得网络拥塞状况得以缓解，降低响应时间，提高响应速度。CDN 网络架构在用户侧与源 server 之间构建多个 CDN代理 server，可以降低延迟、 提高 QoS(quality of service)。当用户对所需内容发送请求时， 如果源服务器之前接收到相同内容的请求， 则该请求被 DNS 重定向到离用户最近的 CDN 代理服务器上， 由该代理服务器发送相应内容给用户。因此， 源服务器只需要将内容发给各个代理服务器， 便于用户从就近的带宽充足的代理服务器上获取内容， 降低网络时延并提高用户体验。随着云计算、 移动互联网及动态网络内容技术的推进， 内容分发技术逐步趋向于专业化、 定制化，在内容路由、 管理、 推送以及安全性方面都面临新的挑战。

在未来 5G 网络中， 随着智能移动终端的不断普及和快速发展的应用服务， 用户对移动数据业务需求量将不断增长， 对业务服务质量的要求也不断提升。CDN 技术的优势正是为用户快速地提供信息服务，同时有助于解决网络拥塞问题。因此，CDN技术成为 5G 必备的关键技术之一。

### D2D 通信

在未来 5G 网络中， 网络容量、 频谱效率需要进一步提升，更丰富的通信模式以及更好的终端用户体验也是 5G 的演进方向。设备到设备通信 ( device-to-device communication，D2D) 具有潜在的提升系统性能、 增强用户体验、 减轻基站压力、 提高频谱利用率的前景。因此， D2D 是未来 5G 网络中的关键技术之一。

D2D 通信是一种基于蜂窝系统的近距离数据直接传输技术。D2D 会话的数据直接在终端之间进行传输， 不需要通过基站转发， 而相关的控制信令，如会话的建立、 维持、 无线资源分配以及计费、 鉴权、 识别、 移动性管理等仍由蜂窝网络负责 。蜂窝网络引入 D2D 通信， 可以减轻基站负担， 降低端到端的传输时延， 提升频谱效率， 降低终端发射功率。当无线通信基础设施损坏， 或者在无线网络的覆盖盲区，终端可借助 D2D 实现端到端通信甚至接入蜂窝网络。在 5G 网络中， 既可以在授权频段部署 D2D 通信，也可在非授权频段部署。

-----

{% img /gallery/origin/0004-5GDemo.jpg 500 5G Demo %}
<p align="center"><b>5G Demo</b></p>

------

### M2M 通信

M2M(machine to machine， M2M)作为物联网在现阶段最常见的应用形式， 在智能电网、 安全监测、城市信息化、 环境监测等领域实现了商业化应用。3GPP 已经针对 M2M 网络制定了一些标准， 并已立项开始研究 M2M 关键技术。根据美国咨询机构FORRESTER 预测估计， 到 2020 年， 全球物与物之间的通信将是人与人之间通信的 30 倍。IDC 预测，在未来的 2020 年，500 亿台 M2M 设备将活跃在全球移动网络中。M2M 市场蕴藏着巨大的商机。因此，研究 M2M 技术对 5G 网络具有非比寻常的意义。

M2M 的定义主要有广义和狭义 2 种。广义的M2M 主要是指机器对机器、 人与机器间以及移动网络和机器之间的通信， 它涵盖了所有实现人、 机器、系统之间通信的技术;从狭义上说， M2M 仅仅指机器与机器之间的通信。智能化、 交互式是 M2M 有别于其它应用的典型特征， 这一特征下的机器也被赋予了更多的“智慧”。

### 信息中心网络

随着实时音频、 高清视频等服务的日益激增，基于位置通信的传统 TCP /IP 网络无法满足海量数据流量分发的要求。网络呈现出以信息为中心的发展趋势。信 息 中 心 网 络 ( information-centric network，ICN)的思想最早是 1979 年由 Nelson 提出来的 ，后来被 Baccala 强化 。目前， 美国的 CCN、 DONA和 NDN 等多个组织对 ICN 进行了深入研究。作为一种新型网络体系结构，ICN 的目标是取代现有的 IP。

ICN 所指的信息包括实时媒体流、 网页服务、 多媒体通信等，而信息中心网络就是这些片段信息的总集合。因此，ICN 的主要概念是信息的分发、 查找和传递，不再是维护目标主机的可连通性。不同于传统的以主机地址为中心的 TCP /IP 网络体系结构，ICN 采用的是以信息为中心的网络通信模型， 忽略 IP 地址的作用， 甚至只是将其作为一种传输标识。全新的网络协议栈能够实现网络层解析信息名称、 路由缓存信息数据、 多播传递信息等功能， 从而较好地解决计算机网络中存在的扩展性、 实时性以及动态性等问题。ICN 信息传递流程是一种基于发布订阅方式的信息传递流程。首先，内容提供方向网络发布自己所拥有的内容，网络中的节点就明白当收到相关内容的请求时如何响应该请求。然后，当第一个订阅方向网络发送内容请求时，节点将请求转发到内容发布方，内容发布方将相应内容发送给订阅方， 带有缓存的节点会将经过的内容缓存。其他订阅方对相同内容发送请求时，邻近带缓存的节点直接将相应内容响应给订阅方。因此，信息中心网络的通信过程就是请求内容的匹配过程。传统 IP 网络中， 采用的是“推” 传输模式，即服务器在整个传输过程中占主导地位， 忽略了用户的地位， 从而导致用户端接收过多的垃圾信息。ICN 网络正好相反， 采用“拉” 模式， 整个传输过程由用户的实时信息请求触发， 网络则通过信息缓存的方式，实现快速响应用户。此外，信息安全只与信息自身相关，而与存储容器无关。针对信息的这种特性，ICN 网络采用有别于传统网络安全机制的基于信息的安全机制。这种机制更加合理可信， 且能实现更细的安全策略粒度。和传统的 IP 网络相比，ICN 具有高效性、 高安全性且支持客户端移动等优势。目前比较典型的 ICN 方案有 CCN， DONA，NetInf，INS 和 TRIAD。

### 移动云计算

近年来，智能手机、 平板电脑等移动设备的软硬件水平得到了极大地提高，支持大量的应用和服务，为用户带来了很大的方便 。在 5G 时代，全球将会出现 500 亿连接的万物互联服务，人们对智能终端的计算能力以及服务质量的要求越来越高。移动云计算将成为 5G 网络创新服务的关键技术之一。移动云计算是一种全新的 IT 资源或信息服务的交付与使用模式， 它是在移动互联网中引入云计算的产物。移动网络中的移动智能终端以按需、 易扩展的方式连接到远端的服务提供商， 获得所需资源，主要包含基础设施、 平台、 计算存储能力和应用资源。SaaS 软件服务为用户提供所需的软件应用，终端用户不需要将软件安装在本地的服务器中，只需要通过网络向原始的服务提供者请求自己所需要的功能软件。PaaS 平台的功能是为用户提供创建、 测试和部署相关应用等服务。PaaS 自身不仅拥有很好的市场应用场景， 而且能够推进 SaaS。而 IaaS 基础设施提供基础服务和应用平台。

### SDN /NFV

随着网络通信技术和计算机技术的发展， 互联网 + 、 三网融合、 云计算服务等新兴产业对互联网在可扩展性、 安全性、 可控可管等方面提出了越来越高的要求。SDN(software-defined networking， 软件定义网络) /NFV(network function virtualization，网络功能虚拟化)作为一种新型的网络架构与构建技术， 其倡导的控制与数据分离、 软件化、 虚拟化思想， 为突破现有网络的困境带来了希望。在欧盟公布的 5G 愿景中， 明确提出将利用 SDN /NFV 作为基础技术支撑未来 5G 网络发展。SDN 架构的核心特点是开放性、 灵活性和可编程性。主要分为 3 层:基础设施层位于网络最底层，包括大量基础网络设备，该层根据控制层下发的规则处理和转发数据;中间层为控制层，该层主要负责对数据转发面的资源进行编排，控制网络拓扑、 收集全局状态信息等;最上层为应用层，该层包括大量的应用服务，通过开放的北向 API 对网络资源进行调用。

SDN 将网络设备的控制平面从设备中分离出来， 放到具有网络控制功能的控制器上进行集中控制。控制器掌握所有必需的信息， 并通过开放的 API 被上层应用程序调用。这样可以消除大量手动配置的过程，简化管理员对全网的管理， 提高业务部署的效率。SDN 不会让网络变得更快， 但他会让整个基础设施简化，降低运营成本， 提升效率。未来 5G 网络中需要将控制与转发分离，进一步优化网络的管理，以 SDN 驱动整个网络生态系统。

### 软件定义无线网络

目前，无线网络面临着一系列的挑战。首先，无线网络中存在大量的异构网络， 如: LTE、 Wimax、UMTS、 WLAN 等，异构无线网络并存的现象将持续相当长的一段时间。目前， 异构无线网络面临的主要挑战是难以互通，资源优化困难，无线资源浪费，这主要是由于现有移动网络采用了垂直架构的设计模式。此外， 网络中的一对多模型( 即单一网络特性对多种服务)，无法针对不同服务的特点提供定制的网络保障，降低了网络服务质量和用户体验。因此，在无线网络中引入 SDN 思想将打破现有无线网络的封闭僵化现象，彻底改变无线网络的困境。

软件定义无线网络保留了 SDN 的核心思想， 即将控制平面从分布式网络设备中解耦， 实现逻辑上的网络集中控制，数据转发规则由集中控制器统一下发。软件定义无线网络的架构分为 3 个层面。在软件定义无线网络中， 控制平面可以获取、更新、预测全网信息，例如:用户属性、动态网络需求以及实时网络状态。因此，控制平面能够很好地优化和调整资源分配、转发策略、流表管理等，简化了网络管理，加快了业务创新的步伐。

### 情境感知技术

随着海量设备的增长， 未来的 5G 网络不仅承载人与人之间的通信， 而且还要承载人与物之间以及物与物之间的通信，既可支撑大量终端，又使个性化、 定制化的应用成为常态。情境感知技术能够让未来 5G 网络主动、 智能、 及时地向用户推送所需的信息。