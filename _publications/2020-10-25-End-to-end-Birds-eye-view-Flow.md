---
title: "End-to-end Birds-eye-view Flow Estimation for Autonomous Driving"
collection: publications
permalink: /publication/2020-10-25-End-to-end-Birds-eye-view-Flow
excerpt: "An end-to-end deep learning framework for LIDAR-based flow estimation in 2.5D bird's eye view (BeV). We show it boosts tracking performance on a real-world autonomous car."
date: 2020-10-25
venue: "IROS 2020"
venuetype: "conference"
paperauthors: 'KH. Lee, M. Kliemann, A. Gaidon, J. Li, C. Fang, S. Pillai, W. Burgard'
thumbnail: "pillarflow1.gif"
tags:
   - IROS2020
   - flow
   - tracking
---

Links: [arxiv](https://arxiv.org/abs/2008.01179), [bibtex](#bibtex)

![Pillarflow results](/images/pillarflow2.gif)

### Abtract

In autonomous driving, accurately estimating the state of surrounding obstacles is critical for safe and robust path planning. However, this perception task is difficult, particularly for generic obstacles/objects, due to appearance and occlusion changes. To tackle this problem, we propose an end-to-end deep learning framework for LIDAR-based flow estimation in bird's eye view (BeV). Our method takes consecutive point cloud pairs as input and produces a 2-D BeV flow grid describing the dynamic state of each cell. The experimental results show that the proposed method not only estimates 2-D BeV flow accurately but also improves tracking performance of both dynamic and static objects.

![Pillarflow architecture](/images/pillarflow-architecture.jpg)

### Bibtex

    @inproceedings{lee2020endtoend,
        title={End-to-end Birds-eye-view Flow Estimation for Autonomous Driving},
        author={Kuan-Hui Lee and Matthew Kliemann and Adrien Gaidon and Jie Li and Chao Fang and Sudeep Pillai and Wolfram Burgard},
        booktitle={IROS},
        year={2020},
    }