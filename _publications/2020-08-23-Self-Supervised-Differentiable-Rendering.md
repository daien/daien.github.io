---
title: "Monocular Differentiable Rendering for Self-Supervised 3D Object Detection"
collection: publications
permalink: /publication/2020-08-23-Self-Supervised-Differentiable-Rendering
excerpt: "Novel self-supervised method for textured 3D shape reconstruction and pose estimation of rigid objects with the help of strong shape priors and 2D instance masks."
date: 2020-08-23
venue: "ECCV 2020"
venuetype: "conference"
paperauthors: 'D. Beker, H. Kato, MA. Morariu, T. Ando, T. Matsuoka, W. Kehl, A. Gaidon'
thumbnail: "self-supervised-dr-eccv-fig-1.jpg"
---

Links: [ECCV 2020 page](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3794_ECCV_2020_paper.php), [ECCV 2020 pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660511.pdf), [openreview](https://openreview.net/forum?id=bKuIk86iZS), arxiv (coming soon), [bibtex](#bibtex)

![Self-supervised Differentiable Rendering overview](/images/self-supervised-dr-eccv-fig-1.jpg)

### Abstract

3D object detection from monocular images is an ill-posed problem due to the projective entanglement of depth and scale. To overcome this ambiguity, we present a novel self-supervised method for textured 3D shape reconstruction and pose estimation of rigid objects with the help of strong shape priors and 2D instance masks. Our method predicts the 3D location and meshes of each object in an image using differentiable rendering and a self-supervised objective derived from a pretrained monocular depth estimation network. We use the KITTI 3D object detection dataset to evaluate the accuracy of the method. Experiments demonstrate that we can effectively use noisy monocular depth and differentiable rendering as an alternative to expensive 3D ground-truth labels or LiDAR information.

### Bibtex

    @inproceedings{beker2020self,
        title={Self-Supervised Differentiable Rendering for Monocular 3D Object Detection},
        author={Deniz Beker and Hiroharu Kato and Mihai Adrian Morariu and Takahiro Ando and Toru Matsuoka and Wadim Kehl and Adrien Gaidon},
        booktitle={ECCV},
        year={2020},
    }
