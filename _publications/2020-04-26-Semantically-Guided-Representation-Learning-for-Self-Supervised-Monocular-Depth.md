---
title: "Semantically-Guided Representation Learning for Self-Supervised Monocular Depth"
collection: publications
permalink: /publication/2020-04-26-Semantically-Guided-Representation-Learning-for-Self-Supervised-Monocular-Depth
excerpt: "A new architecture leveraging fixed pretrained semantic segmentation networks to guide self-supervised representation learning via pixel-adaptive convolutions."
date: 2020-04-26
venue: "ICLR 2020"
venuetype: "conference"
paperauthors: 'V. Guizilini, R. Hou, J. Li, R. Ambrus, A. Gaidon'
thumbnail: "iclr2020-semguided-packnet-thumbnail.jpg"
tags:
   - ICLR2020
   - monocular depth estimation
   - self-supervised learning
   - learning from videos
   - semantic segmentation
   - pixel-adaptive convolutions
   - autonomous driving
   - deep learning
---

Links: [arxiv](https://arxiv.org/abs/2002.12319), [code](https://github.com/TRI-ML/packnet-sfm), [OpenReview](https://openreview.net/forum?id=ByxT7TNFvH), [bibtex](#bibtex)

![ICLR 2020 semguided packnet overview](/images/iclr-2020-semguided-teaser.jpg)

### Abtract

Self-supervised learning is showing great promise for monocular depth estimation, using geometry as the only source of supervision. Depth networks are indeed capable of learning representations that relate visual appearance to 3D properties by implicitly leveraging category-level patterns. In this work we investigate how to leverage more directly this semantic structure to guide geometric representation learning, while remaining in the self-supervised regime. Instead of using semantic labels and proxy losses in a multi-task approach, we propose a new architecture leveraging fixed pretrained semantic segmentation networks to guide self-supervised representation learning via pixel-adaptive convolutions. Furthermore, we propose a two-stage training process to overcome a common semantic bias on dynamic objects via resampling. Our method improves upon the state of the art for self-supervised monocular depth prediction over all pixels, fine-grained details, and per semantic categories.

![ICLR 2020 semguided packnet architecture](/images/iclr-2020-semguided-archi.jpg)

### Bibtex

    @inproceedings{guizilini2020semanticallyguided,
        title={Semantically-Guided Representation Learning for Self-Supervised Monocular Depth},
        author={Vitor Guizilini and Rui Hou and Jie Li and Rares Ambrus and Adrien Gaidon},
        booktitle={ICLR},
        year={2020},
    }