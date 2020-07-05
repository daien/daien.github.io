---
title: "Differentiable Rendering: A Survey"
collection: publications
permalink: /publication/2020-06-22-arxiv-Differentiable-Rendering-Survey
excerpt: "This paper reviews existing literature and discusses the current state of differentiable rendering, its applications, and open research problems."
date: 2020-06-22
paperauthors: 'H. Kato, D. Beker, M. Morariu, T. Ando, T. Matsuoka, W. Kehl, A. Gaidon'
header:
  image: "differentiable-rendering-survey.png"
---

Links: [arxiv](https://arxiv.org/abs/2006.12057)

    @misc{kato2020differentiable,
        title={Differentiable Rendering: A Survey},
        author={Hiroharu Kato and Deniz Beker and Mihai Morariu and Takahiro Ando
            and Toru Matsuoka and Wadim Kehl and Adrien Gaidon},
        year={2020},
        eprint={2006.12057},
        archivePrefix={arXiv},
    }

**Abstract**:

Deep neural networks (DNNs) have shown remarkable performance improvements on vision-related tasks such as object detection or image segmentation. Despite their success, they generally lack the understanding of 3D objects which form the image, as it is not always possible to collect 3D information about the scene or to easily annotate it. Differentiable rendering is a novel field which allows the gradients of 3D objects to be calculated and propagated through images. It also reduces the requirement of 3D data collection and annotation, while enabling higher success rate in various applications. This paper reviews existing literature and discusses the current state of differentiable rendering, its applications and open research problems.

![Differentiable rendering training overview](/images/differentiable-rendering-survey-2.png)
![Differentiable rendering libraries overview](/images/differentiable-rendering-survey-3.png)