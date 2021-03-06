---
layout: post
title: "涌现中的架构（一）"
date: 2017-04-04 17:43:06 +0800
comments: true
tags: ["架构","敏捷"]
series: ["涌现中的架构 0"]
published: true
---



之前对敏捷架构的思考和实践主要在敏捷团队内部[^1]。这个系列主要探讨在公司级别的敏捷架构实践。

<!--more-->

在实行敏捷风格架构的场景中，各个团队将按照自己的实际情况和各自对架构的理解完成架构活动。

作为全局架构师角色，不再进行提前的统一的架构设计。主要工作集中在对架构活动的辅导、服务和审核。 

工作主要在几个方面 - 

1. 架构结果不能相互抵触。

   各团队产出各种组件，它们之间必须能够协作。各个团队的设计结果必须遵从协作协议。要么是既有的，要么是及时达成的。

2. 上层结构需要持续维护。

   跨团队的涌现架构需要一些上层结构的支持[^2]。团队设计的结果随时可能对高层结构产生影响，这时候需要判断这种影响是否是良性的。进而决策是鼓励还是遏制这种影响。

3. 架构活动需要保持某种一致。

   各个团队解决问题的方式需要某种程度的一致性，如果彼此相差太多，就会造成系统难以理解。对演进和传承都有不良的影响。但如果过于强调一致性，又有僵化的趋势，等于走回到计划型架构的老路。

4. 架构设计有时可能需要干预。

   敏捷和涌现的架构是我们的目标。但有些团队可能需要一些帮助才能做到。设计能力方面可能有待提高，认识理念方面可能需要统一。这些团队需要比较频密的干预和辅导。

几个问题需要在实践中探索 -

1. 是否要规定架构设计的产出物？

   可能需要某种程度的统一产出物，以便全局架构师审核和其他团队参考。

2. 如何找到合适的沟通时间点？

   架构设计会在团队间产生相互影响，当团队的节奏不同时，如何找到对彼此影响较小的时间点？

3. 是否需要集中的架构研讨会议？

   团队间的架构沟通是否可以通过一个集中的会议来减少成本？


[^1]: 之前总结的一个系列，时间比较久了。—— [Series: 敏捷的架构设计](/filter/filter.html?filterName=series&filterValue=敏捷的架构设计&filterDes=Series%3A%20敏捷的架构设计)
[^2]: 后续会讨论下这些个结构，其中一个比较明显的可能是：有界上下文。之前也有博文提到过这个结构的应用。—— [Series: 重构，以知识结构为中心](/filter/filter.html?filterName=series&filterValue=重构，以知识结构为中心&filterDes=Series%3A%20重构，以知识结构为中心)

