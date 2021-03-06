---
layout: post
share: true
title: Network In Network
date: 2018-03-24 19:58:38 +0000
author:
  name: Satwik Bhattamishra
  email: satwik55@gmail.com
categories:
- General Deep Learning
tags:
- Medium
- Theory
- Application
---
**Abstract:** We propose a novel deep network structure called “Network In Network”(NIN) to enhance model discriminability for local patches within the receptive field. The conventional convolutional layer uses linear filters followed by a nonlinear activation function to scan the input. Instead, we build micro neural networks with more complex structures to abstract the data within the receptive field. We instantiate the micro neural network with a multilayer perceptron, which is a potent function approximator. The feature maps are obtained by sliding the micro networks over the input in a similar manner as CNN; they are then fed into the next layer. Deep NIN can be implemented by stacking multiple of the above described structure. With enhanced local modeling via the micro network, we are able to utilize global average pooling over feature maps in the classification layer, which is easier to interpret and less prone to overfitting than traditional fully connected layers. We demonstrated the state-of-the-art classification performances with NIN on CIFAR-10 and CIFAR-100, and reasonable performances on SVHN and MNIST datasets.

**Paper Link:** [https://arxiv.org/pdf/1312.4400.pdf](https://arxiv.org/pdf/1312.4400.pdf)

**Task:** Implement the described network architecture explained in the paper in python using TensorFlow, Numpy, Pytorch or MXNet. Test your implementation on MNIST or Basic MNIST dataset.

