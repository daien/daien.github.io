---
title: "Risk-Sensitive Sequential Action Control with Multi-Modal Human Trajectory Forecasting for Safe Crowd-Robot Interaction"
collection: publications
permalink: /publication/2020-10-25-Risk-Sensitive-Control-Trajectron
excerpt: "An online framework for safe and efficient crowd-robot interaction using sampling based trajectory forecasting with risk-sensitive optimal control."
date: 2020-10-25
venue: "IROS 2020"
venuetype: "conference"
paperauthors: 'H. Nishimura, B. Ivanovic, A. Gaidon, M. Pavone, M. Schwager'
thumbnail: "rssac-trajectron-teaser.jpg"
tags:
   - IROS2020
   - trajectory forecasting
   - prediction
   - planning
   - control
---

Links: [arxiv](https://arxiv.org/abs/2009.05702), [video](#video), [bibtex](#bibtex)

![RSSAC Trajectron architecture](/images/rssac-trajectron.jpg)

### Abtract

This paper presents a novel online framework for safe crowd-robot interaction based on risk-sensitive stochastic optimal control, wherein the risk is modeled by the entropic risk measure. The sampling-based model predictive control relies on mode insertion gradient optimization for this risk measure as well as Trajectron++, a state-of-the-art generative model that produces multimodal probabilistic trajectory forecasts for multiple interacting agents. Our modular approach decouples the crowd-robot interaction into learning-based prediction and model-based control, which is advantageous compared to end-to-end policy learning methods in that it allows the robot's desired behavior to be specified at run time. In particular, we show that the robot exhibits diverse interaction behavior by varying the risk sensitivity parameter. A simulation study and a real-world experiment show that the proposed online framework can accomplish safe and efficient navigation while avoiding collisions with more than 50 humans in the scene.

### Video

{% include youtube_embed.html id="iTcmc-ZzxBM" %}

### Bibtex

    @inproceedings{nishimura2020risk,
        title={Risk-Sensitive Sequential Action Control with Multi-Modal Human Trajectory Forecasting for Safe Crowd-Robot Interaction},
        author={Haruki Nishimura and Boris Ivanovic and Adrien Gaidon and Marco Pavone and Mac Schwager},
        booktitle={IROS},
        year={2020},
    }