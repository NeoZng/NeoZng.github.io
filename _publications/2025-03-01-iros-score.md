---
title: "SCORE: Saturated Consensus Relocalization in Semantic Line Maps"
collection: publications
permalink: /publication/score-relocalization
excerpt: '为了解决视觉重定位中存在大量外点、地图表示占用过大空间的问题，提出一种仅使用语义标签的线表示，通过Perspective-N-Lines进行鲁棒视觉重定位的框架。使用带饱和函数的加速分支限界算法进行二阶段的旋转和平移求解以实现在99%外点匹配下的鲁棒估计。'
date: 2025-03-01
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025)'
paperurl: 'https://arxiv.org/pdf/2503.03254'
citation: 'Li Q., Zeng Q., et al. (2025). &quot;SCORE: Saturated Consensus Relocalization in Semantic Line Maps.&quot; <i>IEEE IROS 2025</i>.'
---

为了解决视觉重定位中存在大量外点、地图表示占用过大空间的问题，提出一种仅使用语义标签的线表示，通过Perspective-N-Lines进行鲁棒视觉重定位的框架。使用带饱和函数的加速分支限界算法进行二阶段的旋转和平移求解以实现在99%外点匹配下的鲁棒估计。

我负责饱和函数的设计与理论保证推导，以及代码的C++并行加速实现。

[Paper](https://arxiv.org/pdf/2503.03254) | [Code](https://github.com/LIAS-CUHKSZ/SCORE)