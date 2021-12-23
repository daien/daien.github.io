---
title: "Sparse Auxiliary Networks for Unified Monocular Depth Prediction and Completion"
collection: publications
permalink: /publication/2021-06-19-Sparse-Auxiliary-Networks-for-Unified-Monocular-Depth-Prediction-and-Completion
excerpt: "Learning a single network for dialable depth perception, with or without sparse LiDAR input."
date: 2021-06-19
venue: "CVPR 2021"
venuetype: "conference"
paperauthors: 'V. Guizilini, R. Ambrus, W. Burgard, A. Gaidon'
thumbnail: "CVPR2021-packnet-san.gif"
tags:
   - CVPR2021
   - monocular depth estimation
   - self-supervised learning
   - structure-from-motion
   - learning from videos
   - dialable perception
   - autonomous driving
   - deep learning
---

Links: [arxiv](https://arxiv.org/abs/2103.16690), [code](https://github.com/TRI-ML/packnet-sfm), [bibtex](#bibtex)

![CVPR 2021 PackNet-SAN teaser](/images/CVPR2021-packnet-san.gif)

### Abstract

Estimating scene geometry from data obtained with cost-effective sensors is key for robots and self-driving cars. In this paper, we study the problem of predicting dense depth from a single RGB image (monodepth) with optional sparse measurements from low-cost active depth sensors. We introduce Sparse Auxiliary Networks (SANs), a new module enabling monodepth networks to perform both the tasks of depth prediction and completion, depending on whether only RGB images or also sparse point clouds are available at inference time. First, we decouple the image and depth map encoding stages using sparse convolutions to process only the valid depth map pixels. Second, we inject this information, when available, into the skip connections of the depth prediction network, augmenting its features. Through extensive experimental analysis on one indoor (NYUv2) and two outdoor (KITTI and DDAD) benchmarks, we demonstrate that our proposed SAN architecture is able to simultaneously learn both tasks, while achieving a new state of the art in depth prediction by a significant margin.


### Bibtex

    @inproceedings{guizilini2021san,
        title={Sparse Auxiliary Networks for Unified Monocular Depth Prediction and Completion},
        author={Vitor Guizilini and Rares Ambrus and Wolfram Burgard and Adrien Gaidon},
        booktitle={CVPR},
        year={2021},
    }
