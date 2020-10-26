---
title: "Neural Ray Surfaces for Self-Supervised Learning of Depth and Ego-motion"
collection: publications
permalink: /publication/2020-08-15-Neural-Ray-Surfaces
excerpt: "Neural Ray Surfaces (NRS) are convolutional networks that represent pixel-wise projection rays, approximating a wide range of cameras. NRS are fully differentiable and can be learned end-to-end from unlabeled raw videos."
date: 2020-08-15
venue: "3DV 2020"
award: "oral"
venuetype: "conference"
paperauthors: 'I. Vasiljevic, V. Guizilini, R. Ambrus, S. Pillai, W. Burgard, G. Shakhnarovich, A. Gaidon'
thumbnail: "neural-ray-surfaces-teaser.jpg"
tags:
   - monocular depth estimation
   - self-supervised learning
   - structure-from-motion
   - learning from videos
   - deep learning
---

Links: [arxiv](https://arxiv.org/abs/2008.06630), [video](#video), [bibtex](#bibtex)

![Neural Ray Surfaces (NRS) Model](/images/neural-ray-surfaces-model.jpg)

### Abtract

Self-supervised learning has emerged as a powerful tool for depth and ego-motion estimation, leading to state-of-the-art results on benchmark datasets. However, one significant limitation shared by current methods is the assumption of a known parametric camera model -- usually the standard pinhole geometry -- leading to failure when applied to imaging systems that deviate significantly from this assumption (e.g., catadioptric cameras or underwater imaging). In this work, we show that self-supervision can be used to learn accurate depth and ego-motion estimation without prior knowledge of the camera model. Inspired by the geometric model of Grossberg and Nayar, we introduce Neural Ray Surfaces (NRS), convolutional networks that represent pixel-wise projection rays, approximating a wide range of cameras. NRS are fully differentiable and can be learned end-to-end from unlabeled raw videos. We demonstrate the use of NRS for self-supervised learning of visual odometry and depth estimation from raw videos obtained using a wide variety of camera systems, including pinhole, fisheye, and catadioptric.

### Video

{% include youtube_embed.html id="4TLJG6WJ7MA" %}

### Bibtex

    @inproceedings{vasiljevic2020neural,
        title={End-to-end Birds-eye-view Flow Estimation for Autonomous Driving},
        author={Igor Vasiljevic and Vitor Guizilini and Rares Ambrus and Sudeep Pillai
            and Wolfram Burgard and Greg Shakhnarovich and Adrien Gaidon},
        booktitle={3DV},
        year={2020},
    }