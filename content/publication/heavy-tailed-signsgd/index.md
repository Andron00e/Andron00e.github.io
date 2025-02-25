---
title: 'Sign Operator for Coping with Heavy-Tailed Noise: High Probability Convergence Bounds with Extensions to Distributed Optimization and Comparison Oracle'
authors:
- Nikita Kornilov
- Philip Zmushko
- Andrei Semenov
- Alexander Gasnikov
- Aleksandr Beznosikov
date: '2025-02-11'
doi: 'https://doi.org/10.48550/arXiv.2502.07923'

abstract: The growing popularity of AI optimization problems involving severely corrupted data has increased the demand for methods capable of handling heavy-tailed noise, i.e., noise with bounded κ-th moment, κ∈(1,2]. For the widely used clipping technique, effectiveness heavily depends on the careful tuning of clipping levels throughout training. In this paper, we demonstrate that using only the sign of the input, without introducing additional hyperparameters, is sufficient to cope with heavy-tailed noise effectively. For smooth non-convex functions, we prove that SignSGD achieves optimal sample complexity Õ (ε−3κ−2κ−1) with high probability for attaining an average gradient norm accuracy of ε. Under the assumption of symmetric noise, we use SignSGD with Majority Voting to extend this bound to the distributed optimization or reduce the sample complexity to Õ (ε−4) in the case of a single worker with arbitrary parameters. Furthermore, we explore the application of the sign operator in zeroth-order optimization with an oracle that can only compare function values at two different points. We propose a novel method, MajorityVote-CompsSGD, and provide the first-known high-probability bound Õ (ε−6) for the number of comparisons under symmetric noise assumption. Our theoretical findings are supported by the superior performance of sign-based methods in training Large Language Models.
tags:
- Source Themes
featured: false

url_pdf: 'https://arxiv.org/pdf/2502.07923'
links:
- name: arXiv
  url: https://arxiv.org/abs/2502.07923
---