---
title: Autolabeling 3D Objects with Differentiable Rendering of SDF Shape Priors"
collection: publications
permalink: /publication/2020-06-16-Autolabeling-3D-Objects-with-Differentiable-Rendering
excerpt: "We present an automatic annotation pipeline to recover 9D cuboids and 3D shapes from pre-trained off-the-shelf 2D detectors and sparse LIDAR data."
date: 2020-06-16
venue: "CVPR 2020"
venuetype: "conference"
award: "oral, top 5.7%"
paperauthors: 'S. Zakharov, W. Kehl, A. Bhargava, A. Gaidon'
thumbnail: "CVPR2020-sdflabel-teaser.gif"
tags:
  - CVPR2020
  - Autolabeling
  - Differentiable Rendering
  - Pose and Shape Optimization
  - Curriculum Learning
  - Object Detection
  - Autonomous Driving
  - 3D Shape Modeling
---

Links: [arxiv](https://arxiv.org/abs/1911.11288), [code](https://github.com/TRI-ML/sdflabel), [video](#video), [bibtex](#bibtex)

![CVPR 2020 SDFLabel teaser](/images/CVPR2020-sdflabel-teaser.gif)

### Abtract

We present an automatic annotation pipeline to recover 9D cuboids and 3D shapes from pre-trained off-the-shelf 2D detectors and sparse LIDAR data. Our autolabeling method solves an ill-posed inverse problem by considering learned shape priors and optimizing geometric and physical parameters. To address this challenging problem, we apply a novel differentiable shape renderer to signed distance fields (SDF), leveraged together with normalized object coordinate spaces (NOCS). Initially trained on synthetic data to predict shape and coordinates, our method uses these predictions for projective and geometric alignment over real samples. Moreover, we also propose a curriculum learning strategy, iteratively retraining on samples of increasing difficulty in subsequent self-improving annotation rounds. Our experiments on the KITTI3D dataset show that we can recover a substantial amount of accurate cuboids, and that these autolabels can be used to train 3D vehicle detectors with state-of-the-art results.

### Video

{% include youtube_embed.html id="Utzj-kfWHP4" %}

### Bibtex

    @inproceedings{zakharov2020autolabeling,
        title={Autolabeling 3D Objects with Differentiable Rendering of SDF Shape Priors},
        author={Sergey Zakharov and Wadim Kehl and Arjun Bhargava and Adrien Gaidon},
        booktitle={CVPR},
        year={2020},
    }
