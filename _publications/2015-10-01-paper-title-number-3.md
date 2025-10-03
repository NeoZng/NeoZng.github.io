---
title: "Distributed Invariant Kalman Filter for Object-level Multi-robot Pose SLAM"
collection: publications
permalink: /publication/distributed-invariant-kalman-filter
excerpt: '提出了一种分布式左不变卡尔曼滤波方法，使用来自Pose-CNN输出的语义对象级别6-DoF估计以及机器人之间的相对位姿测量作为滤波器的观测，并通过协方差交集（covariance intersection）解决机器人间位姿估计未知相关性导致的不确定性估计问题。'
date: 2025-01-01
venue: 'IEEE International Conference on Robotics and Automation (ICRA 2025)'
paperurl: 'https://ieeexplore.ieee.org/document/11128538'
citation: 'Zeng Q., et al. (2025). &quot;Distributed Invariant Kalman Filter for Object-level Multi-robot Pose SLAM.&quot; <i>IEEE ICRA 2025</i>.'
---

提出了一种分布式左不变卡尔曼滤波方法，使用来自Pose-CNN输出的语义对象级别6-DoF估计以及机器人之间的相对位姿测量作为滤波器的观测，并通过协方差交集（covariance intersection）以解决机器人间位姿估计未知相关性导致的不确定性估计过度自信/保守的问题，同时在部分机器人出现观测退化时保证整个分布式系统的鲁棒性。

我们还证明了整个系统的稳定性：对于系统中的每一个机器人，其估计误差期望的平方是有界的。我负责将invariant state dynamics推广到分布式卡尔曼滤波上，以及实验验证和仿真环境的搭建。

[Paper](https://ieeexplore.ieee.org/document/11128538) | [Code](https://github.com/LIAS-CUHKSZ/Distributed-object-based-SLAM)