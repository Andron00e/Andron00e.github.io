---
title: 'Adaptive Regularized Newton Method with Inexact Hessian'
authors:
- Aleksandr Shestakov
- Nail Bashirov
- Andrei Semenov
- Alexander Gasnikov
- Martin Takáč
- Aleksandr Beznosikov
- Dmitry Kamzolov
date: '2025-12-09'
doi: 'https://doi.org/10.48550/arXiv.2512.08775'

abstract: Newton's method is the most widespread high-order method, demanding the gradient and the Hessian of the objective function. However, one of the main disadvantages of Newtons method is its lack of global convergence and high iteration cost. Both these drawbacks are critical for modern optimization motivated primarily by current applications in machine learning. In this paper, we introduce a novel algorithm to deal with these disadvantages. Our method can be implemented with various Hessian approximations, including methods that use only the first-order information. Thus, computational costs might be drastically reduced. Also, it can be adjusted to problems' geometries via the usage of different Bregman divergences. The proposed method converges for nonconvex and convex problems globally and it has the same rates as other well-known methods that lack mentioned properties. We present experiments validating our method performs according to the theoretical bounds and shows competitive performance among other Newton-based methods.
tags:
- Source Themes
featured: false

url_pdf: 'https://arxiv.org/pdf/2512.08775'
links:
- name: arXiv
  url: https://arxiv.org/abs/2512.08775
---