---
title: "Distributed Invariant Kalman Filter for Object-level Multi-robot Pose SLAM"
collection: publications
permalink: /publication/distributed-invariant-kalman-filter
excerpt: 'A distributed left-invariant Kalman filter approach that utilizes semantic object-level 6-DoF estimations from Pose-CNN outputs and relative pose measurements between robots as filter observations. The method addresses uncertainty estimation issues caused by unknown correlations in inter-robot pose estimation through covariance intersection, ensuring system robustness when partial robots experience observation degradation.'
date: 2025-01-01
venue: 'IEEE International Conference on Robotics and Automation (ICRA 2025)'
paperurl: 'https://ieeexplore.ieee.org/document/11128538'
citation: 'Zeng Q., et al. (2025). &quot;Distributed Invariant Kalman Filter for Object-level Multi-robot Pose SLAM.&quot; <i>IEEE ICRA 2025</i>.'
---

A distributed left-invariant Kalman filter approach that utilizes semantic object-level 6-DoF estimations from Pose-CNN outputs and relative pose measurements between robots as filter observations. The method addresses uncertainty estimation issues caused by unknown correlations in inter-robot pose estimation through covariance intersection, ensuring system robustness when partial robots experience observation degradation.

We also proved the stability of the entire system: for each robot in the system, the expected square of its estimation error is bounded.

**My Contributions:** Extended invariant state dynamics to distributed Kalman filtering, conducted experimental validation, and developed the simulation environment.

[Paper](https://ieeexplore.ieee.org/document/11128538) | [Code](https://github.com/LIAS-CUHKSZ/Distributed-object-based-SLAM)