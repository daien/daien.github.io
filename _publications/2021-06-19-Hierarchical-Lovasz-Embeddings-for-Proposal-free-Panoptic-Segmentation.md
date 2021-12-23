---
title: "Hierarchical Lovasz Embeddings for Proposal-free Panoptic Segmentation"
collection: publications
permalink: /publication/2021-06-19-Hierarchical-Lovasz-Embeddings-for-Proposal-free-Panoptic-Segmentation
excerpt: "We learn per pixel feature vectors that simultaneously encode instance- and category-level discriminative information."
date: 2021-06-19
venue: "CVPR 2021"
venuetype: "conference"
paperauthors: 'T. Kerola, J. Li, A. Kanehira, Y. Kudo, A. Vallet, A. Gaidon'
thumbnail: "CVPR2021-hle.jpg"
tags:
   - CVPR2021
   - panoptic segmentation
   - semantic segmentation
   - instance segmentation
   - representation learning
   - autonomous driving
   - deep learning
---

Links: [arxiv](https://arxiv.org/abs/2106.04555), [bibtex](#bibtex)

![CVPR 2021 Hierarchical Lovasz Embeddings](/images/CVPR2021-hle.jpg)

### Abstract

Panoptic segmentation brings together two separate tasks: instance and semantic segmentation. Although they are related, unifying them faces an apparent paradox: how to learn simultaneously instance-specific and category-specific (i.e. instance-agnostic) representations jointly. Hence, state-of-the-art panoptic segmentation methods use complex models with a distinct stream for each task. In contrast, we propose Hierarchical Lovász Embeddings, per pixel feature vectors that simultaneously encode instance- and category-level discriminative information. We use a hierarchical Lovász hinge loss to learn a low-dimensional embedding space structured into a unified semantic and instance hierarchy without requiring separate network branches or object proposals. Besides modeling instances precisely in a proposal-free manner, our Hierarchical Lovász Embeddings generalize to categories by using a simple Nearest-Class-Mean classifier, including for non-instance "stuff" classes where instance segmentation methods are not applicable. Our simple model achieves state-of-the-art results compared to existing proposal-free panoptic segmentation methods on Cityscapes, COCO, and Mapillary Vistas. Furthermore, our model demonstrates temporal stability between video frames.


### Bibtex

    @inproceedings{kerola2021hierarchical,
        title={Hierarchical Lovász Embeddings for Proposal-free Panoptic Segmentation},
        author={Tommi Kerola and Jie Li and Atsushi Kanehira and Yasunori Kudo
        and Alexis Vallet and Adrien Gaidon},
        booktitle={CVPR},
        year={2021},
    }
