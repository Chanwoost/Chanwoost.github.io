---
title: "Sufficient dimension reduction for matrix features"
collection: publications
permalink: /publications/sdr
citation: '<b>Chanwoo Lee</b>. Under review, 2023.'
---

[[Preprint]](https://arxiv.org/pdf/2303.04286.pdf)

## Abstract
We address the problem of sufficient dimension reduction for feature matrices, which arises often in sensor network localization, brain neuroimaging, and electroencephalography analysis. In general, feature matrices have both row- and column-wise interpretations and contain structural information that can be lost with naive vectorization approaches. To address this, we propose a method called principal support matrix machine (PSMM) for the matrix sufficient dimension reduction.
The PSMM converts the sufficient dimension reduction problem into a series of classification problems by dividing the response variables into slices. It effectively utilizes the matrix structure by finding hyperplanes with rank-1 normal matrix that optimally separate the sliced responses. Additionally, we extend our approach to the higher-order tensor case.
Our numerical analysis demonstrates that the PSMM outperforms existing methods and has strong interpretability in real data applications.
