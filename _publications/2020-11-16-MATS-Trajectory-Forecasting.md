---
title: "MATS: An Interpretable Trajectory Forecasting Representation for Planning and Control"
collection: publications
permalink: /publication/2020-11-16-MATS-Trajectory-Forecasting
excerpt: ""
date: 2020-11-16
venue: "CoRL 2020"
venuetype: "conference"
paperauthors: 'B. Ivanovic, A. Elhafsi, G. Rosman, A. Gaidon, M. Pavone'
thumbnail: "mats-teaser.jpg"
tags:
   - CoRL2020
   - trajectory forecasting
   - prediction
   - planning
   - control
---

Links: [arxiv](https://arxiv.org/abs/2009.07517), [code](https://github.com/StanfordASL/MATS), [CoRL page](https://corlconf.github.io/paper_499/), [video](#video), [bibtex](#bibtex)

![MATS idea](/images/mats-figure-1.jpg)

### Abtract

Reasoning about human motion is a core component of modern human-robot interactive systems. In particular, one of the main uses of behavior prediction in autonomous systems is to inform ego-robot motion planning and control. However, a majority of planning and control algorithms reason about system dynamics rather than the predicted agent tracklets that are commonly output by trajectory forecasting methods, which can hinder their integration. Towards this end, we propose Mixtures of Affine Time-varying Systems (MATS) as an output representation for trajectory forecasting that is more amenable to downstream planning and control use. Our approach leverages successful ideas from probabilistic trajectory forecasting works to learn dynamical system representations that are well-studied in the planning and control literature. We integrate our predictions with a proposed multimodal planning methodology and demonstrate significant computational efficiency improvements on a large-scale autonomous driving dataset.

### Video

{% include youtube_embed.html id="ZFJKyZ8-MgE" %}

### Bibtex

    @inproceedings{ivanovic2020mats,
        title={MATS: An Interpretable Trajectory Forecasting Representation for Planning and Control},
        author={Boris Ivanovic and Amine Elhafsi and Guy Rosman and Adrien Gaidon and Marco Pavone},
        booktitle={CoRL},
        year={2020},
    }