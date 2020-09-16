---
title: Dense Visual SLAM with Optical Flow and YOLO
date: 2020-08-13T00:30:28.773Z
draft: false
featured: true
authors:
  - De Huo
  - Yanxuan Lv
  - Zuxin Liu
tags:
  - C++
  - OpenCV
  - SLAM
  - ROS
external_link: https://derichuo.com/project/dense-visual-slam-with-optical-flow/
links:
  - url: https://drive.google.com/file/d/1IDgUCZhH0hJ0CN38UUguj7FwWBmMMv4X/view?usp=sharing
    name: video
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
* Conducted research on dense stereo SLAM in dynamic surroundings with RTAB-MAP on the basis of Visual Odometry.
* Added Optical Flow as well as YOLO for auxiliary support to detect moving objects in frames and ruled them out when extracting feature points and mapping.
* Performed testing of real-time Octo-tree mapping and navigation algorithms in ROS on Nvidia TX2.
* Supervised by [Prof. Baochang Zhang](https://scholar.google.com/citations?user=WH0J_34AAAAJ&hl=en)