---
title: "3D Packing for Self-Supervised Monocular Depth Estimation"
collection: publications
permalink: /publication/2020-06-16-3D-Packing-for-Self-Supervised-Monocular-Depth-Estimation
excerpt: "We introduce a new state of the art in self-supervised monocular depth estimation (PackNet), a new benchmark (DDAD), and weak velocity supervision."
date: 2020-06-16
venue: "CVPR 2020"
venuetype: "conference"
award: "oral, top 5.7%"
paperauthors: 'V. Guizilini, R. Ambrus, S. Pillai, A. Raventos, A. Gaidon'
header:
  image: "CVPR2020-packnet-ddad.gif"
tags:
   - CVPR2020
   - monocular depth estimation
   - self-supervised learning
   - structure-from-motion
   - learning from videos
   - 3D convolutions
   - autonomous driving
   - deep learning
---

Links: [arxiv](https://arxiv.org/abs/1905.02693), [code](https://github.com/TRI-ML/packnet-sfm), [DDAD dataset](https://github.com/TRI-ML/DDAD)

{% include youtube_embed.html id="k63VsRnCXFU" %}

    @inproceedings{guizilini2020packnet,
        title={3D Packing for Self-Supervised Monocular Depth Estimation},
        author={Vitor Guizilini and Rares Ambrus and Sudeep Pillai and Allan Raventos
            and Adrien Gaidon},
        booktitle={CVPR},
        year={2020},
    }

**Abstract**:

Although cameras are ubiquitous, robotic platforms typically rely on active sensors like LiDAR for direct 3D perception. In this work, we propose a novel self-supervised monocular depth estimation method combining geometry with a new deep network, PackNet, learned only from unlabeled monocular videos. Our architecture leverages novel symmetrical packing and unpacking blocks to jointly learn to compress and decompress detail-preserving representations using 3D convolutions. Although self-supervised, our method outperforms other self, semi, and fully supervised methods on the KITTI benchmark. The 3D inductive bias in PackNet enables it to scale with input resolution and number of parameters without overfitting, generalizing better on out-of-domain data such as the NuScenes dataset. Furthermore, it does not require large-scale supervised pretraining on ImageNet and can run in real-time. Finally, we release DDAD (Dense Depth for Automated Driving), a new urban driving dataset with more challenging and accurate depth evaluation, thanks to longer-range and denser ground-truth depth generated from high-density LiDARs mounted on a fleet of self-driving cars operating world-wide.