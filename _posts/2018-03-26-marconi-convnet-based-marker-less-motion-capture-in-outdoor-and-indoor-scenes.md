---
layout: post
share: true
title: MARCOnI—ConvNet-Based MARker-Less Motion Capture in Outdoor and Indoor Scenes
date: 2018-03-26 17:04:32 +0000
author:
  name: Anmol Singhal
  email: f2015069@pilani.bits-pilani.ac.in
categories:
- Computer Vision
tags:
- hard
---
Abstract—Marker-less motion capture has seen great progress, but most state-of-the-art approaches fail to reliably track articulated human body motion with a very low number of cameras, let alone when applied in outdoor scenes with general background. In this paper, we propose a method for accurate marker-less capture of articulated skeleton motion of several subjects in general scenes, indoors and outdoors, even from input filmed with as few as two cameras. The new algorithm combines the strengths of a discriminative image-based joint detection method with a model-based generative motion tracking algorithm through an unified pose optimization energy. The discriminative part-based pose detection method is implemented using Convolutional Networks (ConvNet) and estimates unary potentials for each joint of a kinematic skeleton model. These unary potentials serve as the basis of a probabilistic extraction of pose constraints for tracking by using weighted sampling from a pose posterior that is guided by the model. In the final energy, we combine these constraints with an appearance-based model-to-image similarity term. Poses can be computed very efficiently using iterative local optimization, since joint detection with a trained ConvNet is fast, and since our formulation yields a combined pose estimation energy with analytic derivatives. In combination, this enables to track full articulated joint angles at state-of-the-art accuracy and temporal stability with a very low number of cameras. Our method is efficient and lends itself to implementation on parallel computing hardware, such as GPUs. We test our method extensively and show its advantages over related work on many indoor and outdoor data sets captured by ourselves, as well as data sets made available to the community by other research labs. The availability of good evaluation data sets is paramount for scientific progress, and many existing test data sets focus on controlled indoor settings, do not feature much variety in the scenes, and often lack a large corpus of data with ground truth annotation. We therefore further contribute with a new extensive test data set called MPI-MARCOnI for indoor and outdoor marker-less motion capture that features 12 scenes of varying complexity and varying camera count, and that features ground truth reference data from different modalities, ranging from manual joint annotations to marker-based motion capture results. Our new method is tested on these data, and the data set will be made available to the community.

Paper link : [http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7457717](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7457717 "http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7457717")

Task:  Implement the given paper and test on the MARConi dataset available online