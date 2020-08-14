---
title: Temporal Segmentation of Actions in Videos
date: 2020-08-13T01:04:37.314Z
draft: false
featured: true
authors:
  - De Huo
  - Yanxuan Lv
tags:
  - Python
  - PyTorch
  - HMM
  - Clustering
external_link: https://derichuo.com/project/
links:
  - name: code
    url: https://github.com/tk42635/Weakly-Supervised-TemporalSegmentationn
image:
  filename: featured
  focal_point: Smart
  preview_only: true
---
* Researched on weakly supervised learning of video action segmentation based on Hidden Markov Model with a polymorphic neural network to infer the emission probability of HMM.
* Incorporated spectral clustering of frames’ feature vectors into HMM and decoded the HMM with Viterbi algorithm to acquire optimal action label distribution in a video frame sequence.