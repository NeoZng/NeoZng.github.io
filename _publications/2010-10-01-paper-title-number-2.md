---
title: "Efficient Invariant Kalman Filter for Inertial-based Odometry with Large-sample Environmental Measurements"
collection: publications
permalink: /publication/efficient-invariant-kalman-filter
excerpt: 'An invariant Kalman filter design that models error distribution on the SE₂(3) manifold rather than traditional SO(3)×ℝ³ or SE(3), making the dynamics in error states become linear autonomous systems. This improves observer consistency and eliminates linearization errors. The framework demonstrates superior robustness in sensor-degraded scenarios such as long corridors and white walls.'
date: 2024-02-01
venue: 'IEEE Transactions on Robotics (TRO, under review)'
paperurl: 'https://arxiv.org/pdf/2402.05003.pdf'
citation: 'Li Q., Zeng Q., et al. (2024). &quot;Efficient Invariant Kalman Filter for Inertial-based Odometry with Large-sample Environmental Measurements.&quot; <i>IEEE TRO (under review)</i>.'
---

An invariant Kalman filter design that models error distribution on the SE₂(3) manifold rather than traditional SO(3)×ℝ³ or SE(3), making the dynamics in error states become linear autonomous systems. This improves observer consistency and eliminates linearization errors.

Since LiDAR and cameras can construct a large number of observation equations, we designed an estimator that converges consistently under large-sample observations, providing initial values for iterative Kalman filtering. Benefiting from the complementarity of laser point clouds and cameras in degraded scenarios, combined with IMU priors for body motion and point cloud distortion removal, our framework demonstrates superior robustness in sensor-degraded scenarios such as long corridors and white walls.

**My Contributions:** Responsible for code implementation and validation on datasets and real-world experiments.

[Paper](https://arxiv.org/pdf/2402.05003.pdf) | [Code](https://github.com/LIAS-CUHKSZ/EIKF-VIO-LIO)