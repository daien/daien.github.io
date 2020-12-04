---
title: "Self-Supervised 3D Keypoint Learning for Ego-Motion Estimation"
collection: publications
permalink: /publication/2020-11-16-KP3D-Self-supervised-3D-Kepyoints
excerpt: ""
date: 2020-11-16
venue: "CoRL 2020"
award: "oral"
venuetype: "conference"
paperauthors: 'J. Tang, R. Ambrus, V. Guizilini, S. Pillai, H. Kim, P. Jensfelt, A. Gaidon'
thumbnail: "kp3d-keypoints-small.gif"
tags:
   - CoRL2020
   - self-supervised learning
   - keypoints
   - monocular depth estimation
   - learning from videos
   - localization
---

Links: [arxiv](https://arxiv.org/abs/1912.03426), [CoRL page](https://corlconf.github.io/paper_464/), [video](#video), [code](https://github.com/TRI-ML/KP3D), [bibtex](#bibtex)

![KP3D demo](/images/kp3d-demo-small.gif)

### Abtract

Detecting and matching robust viewpoint-invariant keypoints is critical for visual SLAM and Structure-from-Motion. State-of-the-art learning-based methods generate training samples via homography adaptation to create 2D synthetic views with known keypoint matches from a single image. This approach, however, does not generalize to non-planar 3D scenes with illumination variations commonly seen in real-world videos. In this work, we propose self-supervised learning of depth-aware keypoints directly from unlabeled videos. We jointly learn keypoint and depth estimation networks by combining appearance and geometric matching via a differentiable structure-from-motion module based on Procrustean residual pose correction. We describe how our self-supervised keypoints can be integrated into state-of-the-art visual odometry frameworks for robust and accurate ego-motion estimation of autonomous vehicles in real-world conditions.

### Video

{% include youtube_embed.html id="aU5zzUeKmtg" %}

### Bibtex

    @inproceedings{,
        title={Self-Supervised 3D Keypoint Learning for Ego-Motion Estimation},
        author={Jiexiong Tang and Rares Ambrus and Vitor Guizilini and Sudeep Pillai and Hanme Kim and Patric Jensfelt and Adrien Gaidon},
        booktitle={CoRL},
        year={2020},
    }