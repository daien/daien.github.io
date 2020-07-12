---
title: "Spatio-Temporal Graph for Video Captioning with Knowledge Distillation"
collection: publications
permalink: /publication/2020-06-16-Spatio-Temporal-Graph-for-Video-Captioning
excerpt: "We propose a model that learns to distill spatio-temporal object interactions for video captioning."
date: 2020-06-16
venue: "CVPR 2020"
venuetype: "conference"
paperauthors: 'B. Pan, H. Cai, DA Huang, KH Lee, A. Gaidon, E. Adeli, JC Niebles'
header:
  image: "CVPR2020-video-captioning.gif"
tags:
  - CVPR2020
  - Video Captioning
  - Spatio-Temporal Graph
  - Video Understanding
  - Vision and Language
  - Knowledge Distillation
  - Transformer

---

Links: [arxiv](https://arxiv.org/abs/2003.13942)

{% include youtube_embed.html id="QxHttaZF_Xc" %}


    @inproceedings{pan2020spatiotemporal,
        title={Spatio-Temporal Graph for Video Captioning with Knowledge Distillation},
        author={Boxiao Pan and Haoye Cai and De-An Huang and Kuan-Hui Lee and Adrien Gaidon and Ehsan Adeli and Juan Carlos Niebles},
        booktitle={CVPR},
        year={2020},
    }

**Abstract**:

Video captioning is a challenging task that requires a deep understanding of visual scenes. State-of-the-art methods generate captions using either scene-level or object-level information but without explicitly modeling object interactions. Thus, they often fail to make visually grounded predictions, and are sensitive to spurious correlations. In this paper, we propose a novel spatio-temporal graph model for video captioning that exploits object interactions in space and time. Our model builds interpretable links and is able to provide explicit visual grounding. To avoid unstable performance caused by the variable number of objects, we further propose an object-aware knowledge distillation mechanism, in which local object information is used to regularize global scene features. We demonstrate the efficacy of our approach through extensive experiments on two benchmarks, showing our approach yields competitive performance with interpretable predictions.


![ST Graph CVPR 2020 poster](/images/CVPR2020-Poster-Spatio-Temporal-Graph-for-Video-Captioning-with-Knowledge-Distillation.png)