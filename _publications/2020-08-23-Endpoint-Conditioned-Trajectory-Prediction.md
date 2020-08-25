---
title: "It Is Not the Journey but the Destination: Endpoint Conditioned Trajectory Prediction"
collection: publications
permalink: /publication/2020-08-23-Endpoint-Conditioned-Trajectory-Prediction
excerpt: "Predicted Endpoint Conditioned Network (PECNet) for flexible human trajectory prediction. PECNet infers distant trajectory endpoints to assist in long-range multi-modal trajectory prediction."
date: 2020-08-23
venue: "ECCV 2020"
venuetype: "conference"
award: "oral, top 2%"
paperauthors: 'K. Mangalam, H. Girase, S. Agarwal, K-H. Lee, E. Adeli, J. Malik, A. Gaidon'
thumbnail: "pecnet-thumb.jpg"
---

Links: [arxiv](https://arxiv.org/abs/2004.02025), [project page](https://karttikeya.github.io/publication/htf/), [code](https://github.com/HarshayuGirase/PECNet), [bibtex](#bibtex)

![ECCV 2020 PECNet overview](/images/pecnet-fig1.jpg)

### Abtract

Human trajectory forecasting with multiple socially interacting agents is of critical importance for autonomous navigation in human environments, e.g., for self-driving cars and social robots. In this work, we present Predicted Endpoint Conditioned Network (PECNet) for flexible human trajectory prediction. PECNet infers distant trajectory endpoints to assist in long-range multi-modal trajectory prediction. A novel non-local social pooling layer enables PECNet to infer diverse yet socially compliant trajectories. Additionally, we present a simple "truncation-trick" for improving few-shot multi-modal trajectory prediction performance. We show that PECNet improves state-of-the-art performance on the Stanford Drone trajectory prediction benchmark by ~19.5% and on the ETH/UCY benchmark by ~40.8%.

![PECNet architecture](/images/pecnet-fig2.jpg)

### Bibtex

    @inproceedings{mangalam2020journey,
        title={It Is Not the Journey but the Destination: Endpoint Conditioned Trajectory Prediction},
        author={Karttikeya Mangalam and Harshayu Girase and Shreyas Agarwal and
            Kuan-Hui Lee and Ehsan Adeli and Jitendra Malik and Adrien Gaidon},
        booktitle={ECCV},
        year={2020},
    }