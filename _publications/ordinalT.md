---
title: "Tensor denoising and completion based on ordinal observations"
collection: publications
permalink: /publications/ordinalT
citation: '<b>Chanwoo Lee</b> and Miaoyan Wang. ICML 2020.'
---

[[Journal]](http://proceedings.mlr.press/v119/lee20i.html) [[Preprint]](https://arxiv.org/pdf/2002.06524.pdf) [[Software]](https://cran.r-project.org/web/packages/TensorComplete/index.html)

## Abstract
Higher-order tensors arise frequently in applications such as neuroimaging, recommendation system, social network analysis, and psychological studies. We consider the problem of low-rank tensor estimation from possibly incomplete, ordinal-valued observations. Two related problems are studied, one on tensor denoising and the other on tensor completion. We propose a multi-linear cumulative link model, develop a rank-constrained M-estimator, and obtain theoretical accuracy guarantees. Our mean squared error bound enjoys a faster convergence rate than previous results, and we show that the proposed estimator is minimax optimal under the class of low-rank models. Furthermore, the procedure developed serves as an efficient completion method which guarantees consistent recovery of an order-K (d,…,d)-dimensional low-rank tensor using only O(Kd) noisy, quantized observations. We demonstrate the outperformance of our approach over previous methods on the tasks of clustering and collaborative filtering.
