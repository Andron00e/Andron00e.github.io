---
title: 'Benchmarking Optimizers for Large Language Model Pretraining'
authors:
- Andrei Semenov
- Matteo Pagliardini
- Martin Jaggi
date: '2025-09-01'
doi: 'https://doi.org/10.48550/arXiv.2509.01440'

abstract: The recent development of Large Language Models (LLMs) has been accompanied by an effervescence of novel ideas and methods to better optimize the loss of deep learning models. Claims from those methods are myriad – from faster convergence to removing reliance on certain hyperparameters. However, the diverse experimental protocols used to validate these claims make direct comparisons between methods challenging. This study presents a comprehensive evaluation of recent optimization techniques across standardized LLM pretraining scenarios, systematically varying model size, batch size, and training duration. Through careful tuning of each method, we provide guidance to practitioners on which optimizer is best suited for each scenario. For researchers, our work highlights promising directions for future optimization research. Finally, by releasing our code and making all experiments fully reproducible, we hope our efforts can help the development and rigorous benchmarking of future methods.
tags:
- Source Themes
featured: false

url_pdf: 'https://arxiv.org/pdf/2509.01440'
links:
- name: arXiv
  url: https://arxiv.org/abs/2509.01440
url_code: 'https://github.com/epfml/llm-optimizer-benchmark'
---