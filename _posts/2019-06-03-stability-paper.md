---
layout: post
current: post
cover:  assets/images/thesis-cover.jpg
navigation: True
title: Achieving Generalizable Robustness of Deep Neural Networks by Stability Training
date: 2019-06-03 10:00:00
tags: [Publications, Master's Thesis]
class: post-template
subclass: 'post'
author: jan
---

We study the recently introduced stability training as a general-purpose method to increase the robustness of deep neural networks against input perturbations. In particular, we explore its use as an alternative to data augmentation and validate its performance against a number of distortion types and transformations including adversarial examples. In our image classification experiments using ImageNet data stability training performs on a par or even outperforms data augmentation for specific transformations, while consistently offering improved robustness against a broader range of distortion strengths and types unseen during training, a considerably smaller hyperparameter dependence and less potentially negative side effects compared to data augmentation. This work was first documented in my [Master's Thesis](assets/Master_Thesis.pdf) and led to a paper on the German Conference on Pattern Recognition [arXiv link](https://arxiv.org/abs/1906.00735).