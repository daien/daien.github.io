---
title: "Heteroskedastic and Imbalanced Deep Learning with Adaptive Regularization"
collection: publications
permalink: /publication/2021-01-12-Heteroskedastic-and-Imbalanced-Deep-Learning
excerpt: "We propose a data-dependent regularization technique for heteroskedastic and imbalanced datasets."
date: 2021-01-12
venue: "ICLR 2021"
venuetype: "conference"
paperauthors: 'K. Cao, Y. Chen, J. Lu, N. Arechiga, A. Gaidon, T. Ma'
thumbnail: "HAR.png"
tags:
   - ICLR2021
   - machine learning theory
   - regularization
   - long tail
---

Links: [arxiv](https://arxiv.org/abs/2006.15766), [openreview](https://openreview.net/forum?id=mEdwVCRJuX4), [bibtex](#bibtex)


### Abtract

Real-world large-scale datasets are heteroskedastic and imbalanced -- labels have varying levels of uncertainty and label distributions are long-tailed. Heteroskedasticity and imbalance challenge deep learning algorithms due to the difficulty of distinguishing among mislabeled, ambiguous, and rare examples. Addressing heteroskedasticity and imbalance simultaneously is under-explored. We propose a data-dependent regularization technique for heteroskedastic datasets that regularizes different regions of the input space differently. Inspired by the theoretical derivation of the optimal regularization strength in a one-dimensional nonparametric classification setting, our approach adaptively regularizes the data points in higher-uncertainty, lower-density regions more heavily. We test our method on several benchmark tasks, including a real-world heteroskedastic and imbalanced dataset, WebVision. Our experiments corroborate our theory and demonstrate a significant improvement over other methods in noise-robust deep learning.

### Bibtex

    @inproceedings{cao2021heteroskedastic,
        title={Heteroskedastic and Imbalanced Deep Learning with Adaptive Regularization},
        author={Kaidi Cao and Yining Chen and Junwei Lu and Nikos Arechiga
            and Adrien Gaidon and Tengyu Ma},
        booktitle={ICLR},
        year={2021},
    }