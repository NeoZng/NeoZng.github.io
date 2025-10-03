---
title: "Consistent and Optimal Solution to Camera Motion Estimation"
collection: publications
permalink: /publication/consistent-optimal-camera-motion
excerpt: '通过特殊的误差构造使得本质矩阵估计问题的噪声分布在大量采样时具有渐进高斯性，并可以估计出其方差以消除偏差，之后仅需单步高斯-牛顿迭代，就能得到最大似然意义下最优的估计——使得方差达到克拉默洛下界。'
date: 2024-08-01
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)'
paperurl: 'https://ieeexplore.ieee.org/document/11132316'
citation: 'Zeng Q., et al. (2024). &quot;Consistent and Optimal Solution to Camera Motion Estimation.&quot; <i>IEEE TPAMI</i>.'
---

通过特殊的误差构造使得本质矩阵估计问题的噪声分布在大量采样时具有渐进高斯性，并可以估计出其方差以消除偏差，之后仅需单步高斯-牛顿迭代，就能得到最大似然意义下最优的估计——使得方差达到克拉默洛下界。

我主要负责设计用于生成仿真数据和评估对极几何的测试框架，使用C++复现了数种SOTA相对位姿估计算法并适配对比的learning-based方法。

[Paper](https://ieeexplore.ieee.org/document/11132316) | [Code](https://github.com/LIAS-CUHKSZ/Epipolar_evaluation)