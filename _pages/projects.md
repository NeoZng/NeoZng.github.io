---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Industrial Projects

### WeRide - Multi-sensor Calibration Algorithm
**Research Intern** | *2024.12-2025.6*

* Multi-modal sensor calibration algorithm design and optimization without calibration objects and initial mechanical parameter requirements
* LiDAR-Camera extrinsic parameter validation, operational health monitoring, and online calibration
* **Tech Stack:** Multi-sensor fusion, online calibration, robust estimation

---

## Academic Research Projects

### Optimal and Reinforcement Learning Control for Parallel Multi-DOF Wheel-Legged Robot
**Undergraduate Thesis Project** | *2022.11-2023.05*

Established a simplified second-order inverted pendulum model for a five-link parallel mechanism, derived dynamic equations using Newton-Euler method, and designed an MPC controller with validation in MATLAB Simscape Multibody simulation.

**Key Contributions:**
* **Model Predictive Control**: Implemented SQP solver through CasADi, added model-based spatial controllers to extend robot motion to 3D space, achieving terrain adaptation, dynamic suspension, and center-of-gravity adjustment
* **State Estimation**: Designed multi-sensor fusion state observer using dynamic equations, onboard IMU, and joint motor encoders to determine robot-ground contact state and horizontal velocity, suppressing disturbances and model mismatch effects
* **Reinforcement Learning**: Built multi-terrain environments using IsaacGym, designed targeted rewards for curriculum learning, employed asymmetric actor-critic training to achieve stable locomotion on slopes, stairs, and gravel surfaces

[Simulation Code](https://gitee.com/neozng1/finish-designing) | [Deployment Code](https://gitee.com/hnuyuelurm/balance_chassis)

### Multi-sensor Hardware Timestamp Synchronization System
**Independent Project** | *2023.09-2023.10*

Designed LiDAR-Camera-Inertial-GNSS hardware time synchronization scheme. GPS PPS output is split into two channels: one combined with GPRMC messages inputs to LiDAR as synchronization pulse; the other inputs to STM32 external capture for frequency multiplication, outputting PWM to trigger camera acquisition.

**Technical Highlights:**
* Implemented camera acquisition completion and exposure event callback functions on computing platform, setting camera timestamps based on current frame exposure duration and time difference with GPRMC messages
* Added error handling for camera frame errors and PPS errors
* Achieved microsecond-level time synchronization precision exceeding PTP according to oscilloscope test results

[Project Code](https://github.com/LIAS-CUHKSZ/liv_syn)

---

## Open Source Projects

### Hunan University RoboMaster Team - Captain
**Team Leader** | *2022.03-2023.02*

As team captain, responsible for technical direction formulation and project management, while deeply involved in algorithm development and system architecture design.

**Mobile Target State Estimation Algorithm:**
* Extracted target robot features through morphological operations, validated features using SVM, then extracted known relative position points for PnP to determine pose relative to camera
* Modeled target robot as rigid body with superposed uniform rotation and translation, acceleration following zero-mean Gaussian distribution (Singer model), using feature poses relative to camera as observations with particle filter for state estimation

**Deep Learning Optimization:**
* Modified lightweight CNN detector NanoDet for keypoint detection, added unsupervised teacher-student distillation, performed reparameterization + quantization pruning + OpenVINO deployment
* Completed overall framework for 22/23 team programs including MCU communication and camera ROS2 drivers

**Educational Resource Contributions:**
* Authored popular CV tutorial: [Understanding CV and RoboMaster Algorithms](https://github.com/NeoZng/vision_tutorial)
* Programming introduction knowledge base: [Software Development Primer](https://lapis-router-502.notion.site/6c2937aad3974144965860d1809dcaa9)

**Embedded Framework Development:**
* Designed robot embedded framework [basic_framework](https://gitee.com/hnuyuelurm/basic_framework) (600+ stars) with supporting debugging tutorials and workflows
* Established modern development paradigm using ARM-GNU toolchain, Ozone, and VSCode to replace legacy Keil
* Developed C++-based [powerful_framework](https://gitee.com/hnuyuelurm/powerful_framework)
* Framework deployable on all ST series MCUs, requiring only CubeMX pin-map reconfiguration
* **Awarded RoboMaster 2023 Open Source Award Second Prize**

**Tech Stack:** Computer vision, state estimation, deep learning, embedded development, ROS2, C++