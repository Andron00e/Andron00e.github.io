---
title: 'Gradient-Normalized Smoothness for Optimization with Approximate Hessians'
authors:
- Andrei Semenov
- Martin Jaggi
- Nikita Doikov
date: '2025-06-16'
doi: 'https://doi.org/10.48550/arXiv.2506.13710'

abstract: In this work, we develop new optimization algorithms that use approximate second-order information combined with the gradient regularization technique to achieve fast global convergence rates for both convex and non-convex objectives. The key innovation of our analysis is a novel notion called Gradient-Normalized Smoothness, which characterizes the maximum radius of a ball around the current point that yields a good relative approximation of the gradient field. Our theory establishes a natural intrinsic connection between Hessian approximation and the linearization of the gradient. Importantly, Gradient-Normalized Smoothness does not depend on the specific problem class of the objective functions, while effectively translating local information about the gradient field and Hessian approximation into the global behavior of the method. This new concept equips approximate second-order algorithms with universal global convergence guarantees, recovering state-of-the-art rates for functions with Hölder-continuous Hessians and third derivatives, quasi-self-concordant functions, as well as smooth classes in first-order optimization. These rates are achieved automatically and extend to broader classes, such as generalized self-concordant functions. We demonstrate direct applications of our results for global linear rates in logistic regression and softmax problems with approximate Hessians, as well as in non-convex optimization using Fisher and Gauss-Newton approximations.
tags:
- Source Themes
featured: false

url_pdf: 'https://arxiv.org/pdf/2506.13710'
links:
- name: arXiv
  url: https://arxiv.org/abs/2506.13710
url_code: 'https://github.com/epfml/grad-norm-smooth'
---