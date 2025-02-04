---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}


<!-- ## Global Model Learning for Large Deformation Control of Deformable Linear Objects

* 02/2021 - 08/2022
* Publication: one paper in IEEE T-RO, one paper in IEEE ICRA
* Intelligent Robotic Manipulation Lab, Department of Automation, Tsinghua University
* Advisor: Prof. Xiang Li


<p align="center">
  <img width="60%" src="../files/3D_all.gif">
</p>

We propose a coupled offline and online data-driven method for efficiently learning a global deformation model, allowing for both accurate modeling through offline learning and further updating for new DLOs via online adaptation. We also propose a convex-optimization-based controller and analyze the system's stability using the Lyapunov method. Detailed simulations and real-world experiments demonstrate that our method can efficiently and precisely estimate the deformation model, and achieve large deformation control of untrained DLOs in 2D and 3D dual-arm manipulation tasks better than the existing methods. learning.

[[T-RO Website](https://mingrui-yu.github.io/shape_control_DLO_2/)]
[[ICRA Website](https://mingrui-yu.github.io/shape_control_DLO/)]


## ICRA2022 RoboMaster University Sim2Real Challenge
* 03/2022 - 05/2022
<p align="center">
<iframe width="640" height="360" src="https://player.bilibili.com/player.html?aid=510340759&bvid=BV1zu411i7fw&cid=564452340&page=1" title="bilibili video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

The [RoboMaster University Sim2Real Challenge at ICRA 2022](https://air.tsinghua.edu.cn/robomaster/sim2real_icra22.html) aims to optimize the system performance of a robotic task which consists of perception, navigation and manipulation. The first stage is the simulation stage, in which teams will fus on developing algorithms in a simulated environment and completing the challenge mission. In the simulation stage, our team ranked 4th among all 117 participating teams (according to the task performance). 



## Target Capture of Space Robot

* 12/2021
* Course Project of *Space Robot* Course, Tsinghua University

<p align="center">
<iframe width="640" height="360" src="https://player.bilibili.com/player.html?aid=252657952&bvid=BV1jY411p7Nk&cid=471247927&page=1" title="bilibili video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

In this course project, we propose a scheme for capturing a target satellite out of control using a space robot. The space robot is a service satellite with two robot manipulators. During the on-orbit service, the space robot needs to capture the disabled and spinning target satellite, stop its spinning, restabilize it, and fix it up. We design the robot mechanics and the gripper mechanics, analyze the workspace of the manipulators, and simulate the target capture process based on the PyBullet simulator.

[[课程报告](https://www.jianguoyun.com/p/DcLPcAQQ-9KLBxjT0KUE)] [[Code](https://github.com/Mingrui-Yu/space_robot)]


## Seq-CALC: lightweight and robust deep loop detection for SLAM

* 03/2020 - 05/2020
* Institute of Artificial Intelligence and Robotics, Xi’an Jiaotong University
* Advisor: Prof. Pengju Ren

<p align="center">
  <img width="50%" src="https://raw.githubusercontent.com/Mingrui-Yu/Seq-CALC/master/docs/experiment_KITTI_3d.png">
</p>

We propose a lightweight SLAM loop detection method based on deep learning. An unsupervised denoising auto-encoder network is trained to extract an image’s deep descriptor, which uses the projective-transformed images as input data, and HOG descriptor as the reconstruction object. Besides, we apply PCA to reduce the descriptor’s dimension, and combine linear query with fast approximate nearest neighbor search to further improve the efficiency. With the help of sequence match, we significantly improve its accurary. The results of experiments on NVIDIA TX2 demonstrate that, our Seq-CALC outperforms DBoW3 in terms of both accurary and efficiency on various challenging datasets. Its accuary is even close to NetVLAD under certain conditions. We open-source the C++ library of Seq-CALC, which can be conveniently embedded in any SLAM system.

[[Details](https://mingrui-yu.github.io/Seq-CALC/)] [[Code](https://github.com/Mingrui-Yu/Seq-CALC)] [[本科毕业论文](https://www.jianguoyun.com/p/DVqHhNIQ-9KLBxi40dkD)]


## A simple stereo SLAM system

* 03/2020 - 05/2020
* Institute of Artificial Intelligence and Robotics, Xi’an Jiaotong University

<p align="center">
  <img width="40%" src="https://raw.githubusercontent.com/Mingrui-Yu/A-Simple-Stereo-SLAM-System/master/docs/pics/running.gif">
</p>

This is a simple stereo SLAM system with a deep-learning based loop closure module ([Seq-CALC](https://github.com/Mingrui-Yu/Seq-CALC)). As a beginner of SLAM, I made this system mainly in order to practice my coding and engineering skills to build a full SLAM system by myself. The structure of the system is simple and clear, in which I didn't apply much detailed optimization. Thus, the performance of this system is not outstanding. Such a simple structure may be friendly for a SLAM beginner to study the body frame of a full SLAM system.

[[Details](https://mingrui-yu.github.io/A-Simple-Stereo-SLAM-System/)] [[Code](https://github.com/Mingrui-Yu/A-Simple-Stereo-SLAM-System)]


## An Intelligent Car based on Raspberry Pi

* 10/2019 - 12/2019
* Xi'an Jiaotong University

<p align="center">
  <img width="40%" src="https://i.loli.net/2019/10/31/SpHzE7MBRfkr5aN.gif">
</p>

In this curriculum project, we utilize Raspberry Pi 3 and some other accessories to design a simple intelligent car. The functions we have implemented include obstacle avoidance, video transmittion from Pi to PC, lane tracking, object detection, and tennis tracking.

[[Details](https://mingrui-yu.github.io/RaspberryCar/)] [[Code](https://github.com/Mingrui-Yu/RaspberryCar)]


## Adaptive traffic signal control with deep reinforcement learning 

* 07/2018 - 06/2019
* Institute of Automation, Chinese Academy of Sciences
* Advisor: Prof. Yisheng Lv

Contents:
* Proposed a DRL algorithm that automatically learns an optimal policy to adaptively determine
phase duration.
* Proposed a phase sensitive neural network structure based on DDPG model.
* Developed some interesting training techniques.

[[Paper](https://ieeexplore.ieee.org/document/9327396)] -->

## Image processing in color+depth based 3D vision systems

* 02/2018 - 11/2018
* Institute of Artificial Intelligence and Robotics, Xi’an Jiaotong University
* Advisor: Prof. Meng Yang

Contents:
* Depth-based stereoscopic image zooming.
* Extension and application of Depth No-Synthesis-Error model for view synthesis in 3D video.
* Color guided depth map restoration for synthesized view quality enhancement.




