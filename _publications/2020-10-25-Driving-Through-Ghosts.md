---
title: "Driving Through Ghosts: Behavioral Cloning with False Positives"
collection: publications
permalink: /publication/2020-10-25-Driving-Through-Ghosts
excerpt: "A novel representation of perceptual uncertainty for learning to plan via behaviorial cloning."
date: 2020-10-25
venue: "IROS 2020"
venuetype: "conference"
paperauthors: 'A. Bühler, A. Gaidon, A. Cramariuc, R. Ambrus, G. Rosman, W. Burgard'
thumbnail: "driving-through-ghosts-teaser.jpg"
---

Links: [arxiv](https://arxiv.org/abs/2008.12969), [video](#video), [bibtex](#bibtex)

![Driving Through Ghosts teaser](/images/driving-through-ghosts-teaser.jpg)

### Abtract

Safe autonomous driving requires robust detection of other traffic participants. However, robust does not mean perfect, and safe systems typically minimize missed detections at the expense of a higher false positive rate. This results in conservative and yet potentially dangerous behavior such as avoiding imaginary obstacles. In the context of behavioral cloning, perceptual errors at training time can lead to learning difficulties or wrong policies, as expert demonstrations might be inconsistent with the perceived world state. In this work, we propose a behavioral cloning approach that can safely leverage imperfect perception without being conservative. Our core contribution is a novel representation of perceptual uncertainty for learning to plan. We propose a new probabilistic birds-eye-view semantic grid to encode the noisy output of object perception systems. We then leverage expert demonstrations to learn an imitative driving policy using this probabilistic representation. Using the CARLA simulator, we show that our approach can safely overcome critical false positives that would otherwise lead to catastrophic failures or conservative behavior.

### Video

{% include youtube_embed.html id="2o2F5m1vwS0" %}

### Bibtex

    @inproceedings{buehler2020driving,
        title={Driving Through Ghosts: Behavioral Cloning with False Positives},
        author={Andreas Buehler and Adrien Gaidon and Andrei Cramariuc and Rares Ambrus and Guy Rosman and Wolfram Burgard},
        booktitle={IROS},
        year={2020},
    }