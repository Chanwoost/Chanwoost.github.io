---
title: "Generalized Tensor Decomposition With Features on Multiple Modes"
collection: publications
permalink: /publications/Tregress
citation: 'Jiaxin Hu, <b>Chanwoo Lee</b> and Miaoyan Wang. JCGS, 2021.'
---

[[Journal]](https://www.tandfonline.com/doi/full/10.1080/10618600.2021.1978471) [[Preprint]](https://arxiv.org/abs/1910.09499v2) [[Software]](https://cran.r-project.org/web/packages/tensorregress/index.html)

## Abstract
Higher-order tensors have received increased attention across science and engineering. While most tensor decomposition methods are developed for a single tensor observation, scientific studies often collect side information, in the form of node features and interactions thereof, together with the tensor data. Such data problems are common in neuroimaging, network analysis, and spatial-temporal modeling. Identifying the relationship between a high-dimensional tensor and side information is important yet challenging. Here, we develop a tensor decomposition method that incorporates multiple feature matrices as side information. Unlike unsupervised tensor decomposition, our supervised decomposition captures the effective dimension reduction of the data tensor confined to feature space of interest. An efficient alternating optimization algorithm with provable spectral initialization is further developed. Our proposal handles a broad range of data types, including continuous, count, and binary observations. We apply the method to diffusion tensor imaging data from human connectome project and multi-relational political network data. We identify the key global connectivity pattern and pinpoint the local regions that are associated with available features. Our simulation code, R-package tensorregress, and datasets used in the paper are available at [this https URL](https://cran.r-project.org/web/packages/tensorregress/index.html).
