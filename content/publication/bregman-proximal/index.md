---
title: 'Bregman Proximal Method for Efficient Communications under Similarity'
authors:
- Aleksandr Beznosikov
- Darina Dvinskikh
- Andrei Semenov
- Alexander Gasnikov
date: '2023-11-12'
doi: 'https://doi.org/10.48550/arXiv.2311.06953'

abstract: 

tags:
- Source Themes
featured: false

url_pdf: 'https://arxiv.org/pdf/2311.06953.pdf'
links:
- name: arXiv
  url: https://arxiv.org/abs/2311.06953
---
We propose a novel distributed method for monotone variational inequalities and convex-concave saddle point problems arising in various machine learning applications such as game theory and adversarial training. By exploiting similarity our algorithm overcomes communication bottleneck which is a major issue in distributed optimization. The proposed algorithm enjoys optimal communication complexity of δ/ϵ, where ϵ measures the non-optimality gap function, and  is a parameter of $\textit{similarity}$. All the existing distributed algorithms achieving this bound essentially utilize the Euclidean setup. In contrast to them, our algorithm is built upon Bregman proximal maps and it is compatible with an arbitrary Bregman divergence. Thanks to this, it has more flexibility to fit the problem geometry than algorithms with the Euclidean setup. Thereby the proposed method bridges the gap between the Euclidean and non-Euclidean setting. By using the restart technique, we extend our algorithm to variational inequalities with μ-strongly monotone operator, resulting in optimal communication complexity of δ/μ (up to a logarithmic factor). Our theoretical results are confirmed by numerical experiments on a stochastic matrix game.