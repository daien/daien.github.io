---
title: "Real-Time Panoptic Segmentation from Dense Detections"
collection: publications
permalink: /publication/2020-06-16-Real-Time-Panoptic-Segmentation-from-Dense-Detections
excerpt: "A novel panoptic segmentation method featuring parameter-free instance mask reconstruction, state-of-the-art accuracy, and real-time inference."
date: 2020-06-16
venue: "CVPR 2020"
venuetype: "conference"
award: "oral, top 5.7%"
paperauthors: 'R. Hou, J. Li, A. Bhargava, A. Raventos, V. Guizilini, C. Fang, J Lynch, A. Gaidon'
header:
  image: "CVPR2020-panoptic-teaser.gif"
tags:
  - CVPR2020
  - Panoptic Segmentation
  - Real-time Inference
  - Object Detection
  - Instance Segmentation
  - Semantic Segmentation
  - Self-attention
---

Links: [arxiv](https://arxiv.org/abs/1912.01202), [code](https://github.com/TRI-ML/realtime_panoptic)

{% include youtube_embed.html id="xrxaRU2g2vo" %}


    @inproceedings{hou2020realtime,
        title={Real-Time Panoptic Segmentation from Dense Detections},
        author={Rui Hou and Jie Li and Arjun Bhargava and Allan Raventos and
            Vitor Guizilini and Chao Fang and Jerome Lynch and Adrien Gaidon},
        booktitle={CVPR},
        year={2020},
    }

**Abstract**:

Panoptic segmentation is a complex full scene parsing task requiring simultaneous instance and semantic segmentation at high resolution. Current state-of-the-art approaches cannot run in real-time, and simplifying these architectures to improve efficiency severely degrades their accuracy. In this paper, we propose a new single-shot panoptic segmentation network that leverages dense detections and a global self-attention mechanism to operate in real-time with performance approaching the state of the art. We introduce a novel parameter-free mask construction method that substantially reduces computational complexity by efficiently reusing information from the object detection and semantic segmentation sub-tasks. The resulting network has a simple data flow that does not require feature map re-sampling or clustering post-processing, enabling significant hardware acceleration. Our experiments on the Cityscapes and COCO benchmarks show that our network works at 30 FPS on 1024x2048 resolution, trading a 3% relative performance degradation from the current state of the art for up to 440% faster inference.
