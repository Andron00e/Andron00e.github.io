---
title: "Sparse Concept Bottleneck Models: Gumbel Tricks in Contrastive Learning"
authors:
- Andrei Semenov
- [Vladimir Ivanov](https://scholar.google.com/citations?user=16AyxX0AAAAJ&hl=ru)
- [Aleksandr Beznosikov](https://anbeznosikov.github.io/index.html)
- [Alexander Gasnikov](https://scholar.google.com/citations?user=AmeE8qkAAAAJ&hl=ru)
date: "2024-04-04"
doi: "https://doi.org/10.48550/arXiv.2404.03323"

abstract: "We propose a novel architecture and method of explainable classification with Concept Bottleneck Models (CBMs). While SOTA approaches to Image Classification task work as a black box, there is a growing demand for models that would provide interpreted results. Such a models often learn to predict the distribution over class labels using additional description of this target instances, called concepts. However, existing Bottleneck methods have a number of limitations: their accuracy is lower than that of a standard model and CBMs require an additional set of concepts to leverage. We provide a framework for creating Concept Bottleneck Model from pre-trained multi-modal encoder and new CLIP-like architectures. By introducing a new type of layers known as Concept Bottleneck Layers, we outline three methods for training them: with ℓ1-loss, contrastive loss and loss function based on Gumbel-Softmax distribution (Sparse-CBM), while final FC layer is still trained with Cross-Entropy. We show a significant increase in accuracy using sparse hidden layers in CLIP-based bottleneck models. Which means that sparse representation of concepts activation vector is meaningful in Concept Bottleneck Models. Moreover, with our Concept Matrix Search algorithm we can improve CLIP predictions on complex datasets without any additional training or fine-tuning. The code is available at: https://github.com/Andron00e/SparseCBM."

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://arxiv.org/pdf/2404.03323.pdf'
- name: arXiv
    url: 'https://arxiv.org/abs/2404.03323'
url_code: 'https://github.com/Andron00e/SparseCBM'
---