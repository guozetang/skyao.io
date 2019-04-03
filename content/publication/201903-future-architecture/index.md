+++
title = "未来架构：从服务化到云原生"
date = "2019-03-19"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["敖小剑"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["5"]

# Publication name and optional abbreviated version.
publication = "未来架构：从服务化到云原生"
publication_short = "电子工业出版社"

# Abstract and optional shortened version.
abstract = "互联网架构不断演化，经历了从集中式架构到分布式架构，再到云原生架构的过程。云原生因能解决传统应用升级缓慢、架构臃肿、不能快速迭代等问题而成为未来云端应用的目标。本书首先介绍了架构演化过程及云原生的概念，让读者对基础概念能有一个准确的了解。接着阐述分布式、服务化、Observability、容器调度、Service Mesh、云数据库等体系及其原理，并介绍了与其相关的Dubbo、Spring Cloud、SkyWalking、Kubernetes、Istio开源解决方案。最后深度揭秘开源分布式数据库生态圈Sharding-Sphere的设计与实现ss。<br><br>"
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

tags = ["云原生"]

# Links (optional).
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "书籍介绍@电子工业出版社", url = "https://www.phei.com.cn/module/goods/wssd_content.jsp?bookid=53619"},{name = "书籍销售@京东", url = "https://item.jd.com/12498217.html"}, {name = "书籍销售@当当", url = "http://product.dangdang.com/26912145.html"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/publication/201903-future-architecture.jpg"
caption = ""

+++

本书有多位作者: 张亮、吴晟、敖小剑、宋净超

![](images/cover.jpg)

## 书籍说明

本书的发起人和主笔是 **张亮** 兄，另外两位作者 吴晟 和 宋净超 也是熟识已久多次合作。书籍由电子工业出版社出版，在2019年3月发售。

在2018年年中，我非常荣幸的受邀参与本书的编写，贡献了其中的“第8章 跨语言服务治理方案Service Mesh”——这是我参与编写并出版的第一本实体书。非常巧合的是，这本书在京东开始销售的第一天，3月19号，正是我的生日，算是一份很独特的生日礼物。

## 书籍介绍

> 备注：以下内容转自 张亮 兄的微信公众号"点亮架构"

### 成书缘由

身处互联网行业的我们一向处在变革的最前端，受到世界浪潮的洗礼，不停歇地追赶着这一波又一波的技术潮流，才不会落在时代脚步之后。特别是近几年来，互联网架构不断演化，经历了从集中式架构到分布式架构，再到云原生架构的过程。云原生因能解决传统应用升级缓慢、架构臃肿、不能快速迭代等问题而逐渐成为这个时代舞台的主角。

身处在这个变化浪潮中，我看着它改变着互联网架构的航行方向，并给越来越多的公司和个人带来新的思想和发展，也用我这些年走过的路、积累的经验、沉淀的眼界去学习它、读懂它，并让它融入我的知识体系网，来更新大脑里那张探索不断、充满指南针意义的架构地图。

2017、2018年，我与这些变化同进同退，让Elastic-Job、[Sharding-Sphere](https://github.com/sharding-sphere)成为业界里大家认可的项目、让所负责的开源项目开始走向国际化、也认识了更多的良师益友……这种种的经历和发展，触动我开始将所闻、所见、所知、所感的珠玑落到了笔尖，串联成了这本书：《未来架构——从服务化到云原生》。

这本书里有你想认识的分布式、服务化、服务网格、容器、编排治理、云原生、云数据库……

这本书里既有我多年深思熟虑的见解和沉淀良久的经验，也有我弃笔又拾笔的挣扎，因为我需要让书的内容对读者负责……

这本书里更有这些资深大咖的精彩章节叙述：Apache孵化器项目SkyWalking创始人&APM专家吴晟、CNCF Ambassador&云原生布道师[宋净超](https://jimmysong.io/)、Servicemesher社区联合创始人&ServiceMesh布道师[敖小剑](https://skyao.io/)……

## 内容预览

《未来架构——从服务化到云原生》将互联网架构近几年发展的起承转合进行提炼解读、推陈出新，并和我的这些挚友们共同为大家展示互联网架构的变迁、最新最热技术的深度解读。本书预计于2019年3月中旬发售。也总算能对一直询问这本书进展的读者朋友有所交代了。在发售前，先将书籍目录汇总整理给大家，先睹为快，看是否能命中你所关心的热点技术靶心吧。

```ini
第1章 云原生
  1.1 互联网架构变迁
    1.1.1 互联网架构核心问题
    1.1.2 从集中式到分布式架构
    1.1.3 从分布式到云原生架构
  1.2 什么是云原生
    1.2.1 概述
    1.2.2 云原生与十二要素
    1.2.3 十二要素进阶
    1.2.4 云原生与CNCF
    1.2.5 小结

第2章 远程通信
  2.1 通信方式
    2.1.1 通信协议
    2.1.2 I/O模型
    2.1.3 Java中的I/O

  2.2 序列化
    2.2.1 文本序列化
    2.2.2 二进制Java序列化
    2.2.3 二进制异构语言序列化
    2.2.4 小结
  2.3 远程调用
    2.3.1 核心概念
    2.3.2 Java远程通信RMI
    2.3.3 异构语言RPC框架 gRPC
    2.3.4 小结

第3章 配置
  3.1 本地配置
  3.2 配置集中化
  3.3 配置中心和注册中心
    3.3.1 快速传播
    3.3.2 变更稀疏
    3.3.3 环境相关
  3.4 读性能
    3.4.1 集中式缓存
    3.4.2 本地缓存
  3.5 变更实时性
    3.5.1 监听
    3.5.2 定时同步
  3.6 可用性
    3.6.1 服务冗余
    3.6.2 缓存
  3.7 数据一致性
  3.8 总结

第4章 服务治理
  4.1 服务发现
    4.1.1 概述
    4.1.2 ZooKeeper
    4.1.3 Eureka
    4.1.4 总结
  4.2 负载均衡
    4.2.1 服务端负载均衡
    4.2.2 客户端负载均衡
  4.3 限流
    4.3.1 限流算法
    4.3.2 限流实现方案
    4.3.3 限流的维度与粒度
    4.3.4 小结
  4.4 熔断
    4.4.1 概述
    4.4.2 熔断器模式
    4.4.3 Hystrix

第5章 观察分布式服务
  5.1 层次划分
  5.2 核心概念
  5.3 分布式追踪
  5.4 常见开源解决方案
  5.5 应用性能监控
  5.6 Apache SkyWalking
    5.6.1 项目定位
    5.6.2 SkyWalking 5核心架构
    5.6.3 SkyWalking 5公开案例
    5.6.4 SkyWalking 6可观测性分析平台

第6章 侵入式服务治理方案
  6.1 Dubbo
    6.1.1 概述
    6.1.2 核心流程
    6.1.3 注册中心
    6.1.4 负载均衡
    6.1.5 远程通信
    6.1.6 限流
    6.1.7 治理中心
    6.1.8 监控中心
    6.1.9 DubboX的扩展
  6.2 Spring Cloud
    6.2.1 概述
    6.2.2 开发脚手架Spring Boot
    6.2.3 服务发现
    6.2.4 负载均衡
    6.2.5 熔断
    6.2.6 远程通信
  6.3 总结

第7章 云原生生态的基石Kubernetes
  7.1 Kubernetes架构
  7.2 分层设计理念及架构模型
  7.3 设计哲学
  7.4 Kubernetes中的原语
    7.4.1 Kubernetes中的对象
    7.4.2 对象的期望状态与实际状态
    7.4.3 描述Kubernetes对象
    7.4.4 服务发现与负载均衡
    7.4.5 安全性与权限管理
    7.4.6 Sidecar设计模式
  7.5 应用Kubernetes
  7.6 Kubernetes与云原生生态
    7.6.1 下一代云计算标准
    7.6.2 当前存在的问题
    7.6.3 未来趋势

第8章 跨语言服务治理方案Service Mesh  <-- 本章由我编写
  8.1 介绍
    8.1.1 Service Mesh的由来
    8.1.2 Service Mesh的定义
    8.1.3 Service Mesh详解
  8.2 Service Mesh演进历程
    8.2.1 远古时代的案例
    8.2.2 微服务时代的现状
    8.2.3 侵入式框架的痛点
    8.2.4 解决问题的思路
    8.2.5 Proxy模式的探索
    8.2.6 Sidecar的出现
    8.2.7 第一代Service Mesh
    8.2.8 第二代Service Mesh
    8.2.9 总结

  8.3 Service Mesh市场竞争
    8.3.1 Service Mesh的萌芽期
    8.3.2 急转而下的Linkerd
    8.3.3 波澜不惊的Envoy
    8.3.4 背负使命的Istio
    8.3.5 背水一战的Buoyant
    8.3.6 其他参与者
    8.3.7 Service Mesh国内发展
    8.3.8 总结
  8.4 Istio
    8.4.1 介绍
    8.4.2 架构和核心组件

第9章 云原生数据架构
  9.1 关系型数据库尚能饭否
    9.1.1 优势
    9.1.2 不足
    9.1.3 小结
  9.2 未达预期的NoSQL
    9.2.1 键值数据库
    9.2.2 文档数据库
    9.2.3 列族数据库
    9.2.4 小结

  9.3 冉冉升起的NewSQL
    9.3.1 New Architecture
    9.3.2 Transparent Sharding Middleware
    9.3.3 Database-as-a-Service
    9.3.4 小结
  9.4 云原生数据库中间件的核心功能
    9.4.1 数据分片
    9.4.2 分布式事务
    9.4.3 数据库治理

第10章 分布式数据库中间件生态圈Sharding-Sphere
  10.1 缘起
    10.1.1 内部应用框架
    10.1.2 开源历程
  10.2 核心功能
    10.2.1 数据分片
    10.2.2 分布式事务
    10.2.3 数据库治理
  10.3 Sharding-JDBC
    10.3.1 简介
    10.3.2 使用介绍
  10.4 ShardingProxy
    10.4.1 简介
    10.4.2 使用介绍
  10.5 Database Mesh
    10.5.1 概述
    10.5.2 Service Mesh回顾
    10.5.3 Database Mesh与Service Mesh的异同
    10.5.4 Sharding-Sidecar
  10.6 未来规划
  10.7 社区化
```

### 寄托期翼

书的封页是张亮老师选择的老特拉福德球场前矗立的曼联Holy Trinity雕像作为背景图。

1958年2月6日，曼联队在南斯拉夫参加欧冠杯获得半决赛权后，回程途中遭遇慕尼黑空难，曼联战队瞬间消失在夜空。为了曼联的复兴，幸存下来的曼联队的主帅马特·巴斯比强忍悲痛，用血泪和汗水重建曼联。1968年5月29日，在慕尼黑空难整整10年后，巴斯比带领他的新战队终于捧起了欧洲冠军杯，告慰了那些故去的亡魂！这座Holy Trinity雕像变成了永恒的纪念！

信仰、永不言弃、坚持不懈、创造奇迹、浴火重生…，是我从这座雕塑中感受到的力量。每个人的一生一定都会经历高峰和低谷，见过山川和沙漠，也希望这本书不仅仅能为大家带来互联网架构的干货知识，也能寄托我对大家的祝福：希望在这十万长征路上正在不懈拼搏的你，能够拥有自己的信仰和希望，即使要途径无数沙漠和海洋，也能在经历千帆后柳暗花明！

## 补充说明

本书截稿于2018年10月初，因此“第8章 跨语言服务治理方案Service Mesh”这部分内容，有关Istio/Linkerd等的介绍就只更新到2018年九月，到本书出版发售的2019年3月，有近半年时间。期间 Service Mesh 飞速发展，半年时间有了不少变化，最新的内容可以浏览 [“Service Mesh2018年度总结”](../201902-service-mesh-2018-summary/) 一文（该文发布于2019年2月中）。
