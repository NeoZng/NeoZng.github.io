---
title: "Efficient Invariant Kalman Filter for Inertial-based Odometry with Large-sample Environmental Measurements"
collection: publications
permalink: /publication/efficient-invariant-kalman-filter
excerpt: '根据系统状态的流形特性，不变卡尔曼滤波的设计将误差分布建模在SE₂(3)流形上而非传统的SO(3)×ℝ³或SE(3)，使得误差状态中的动力学变为线性自治系统，从而改善观测器的一致性并消除线性化误差。'
date: 2024-02-01
venue: 'IEEE Transactions on Robotics (TRO, under review)'
paperurl: 'https://arxiv.org/pdf/2402.05003.pdf'
citation: 'Li Q., Zeng Q., et al. (2024). &quot;Efficient Invariant Kalman Filter for Inertial-based Odometry with Large-sample Environmental Measurements.&quot; <i>IEEE TRO (under review)</i>.'
---

根据系统状态的流形特性，不变卡尔曼滤波的设计将误差分布建模在SE₂(3)流形上而非传统的SO(3)×ℝ³或SE(3)，使得误差状态中的动力学变为线性自治系统，从而改善观测器的一致性并消除线性化误差。

激光雷达和相机能构建的观测方程数量通常很大，故设计了在大样本观测情况下一致收敛的估计器，为迭代卡尔曼滤波提供初值。得益于激光点云和相机在对方退化情况下的互补性，加上IMU对机体运动的先验和对点云畸变的去除，我们的框架对于长走廊、白墙等传感器退化的情形表现出卓越的鲁棒性。

我负责代码实现和数据集/实机验证。

[Paper](https://arxiv.org/pdf/2402.05003.pdf) | [Code](https://github.com/LIAS-CUHKSZ/EIKF-VIO-LIO)