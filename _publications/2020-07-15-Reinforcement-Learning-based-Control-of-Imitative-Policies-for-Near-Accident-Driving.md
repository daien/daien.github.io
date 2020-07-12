---
title: "Reinforcement Learning based Control of Imitative Policies for Near-Accident Driving"
collection: publications
permalink: /publication/2020-07-15-Reinforcement-Learning-based-Control-of-Imitative-Policies-for-Near-Accident-Driving
excerpt: "We propose a hierarchical reinforcement and imitation learning (H-ReIL) approach for learning to drive in near-accident scenarios."
date: 2020-07-15
venue: "RSS 2020"
venuetype: "conference"
paperauthors: 'Z. Cao, E. Biyik, W. Z. Wang, A. Raventos, A. Gaidon, G. Rosman, D. Sadigh'
thumbnail: "rss2020-h-reil-1.jpg"
---

Links: [RSS 2020 page](https://roboticsconference.org/program/papers/39/), [video](#video), [arxiv](https://arxiv.org/abs/2007.00178), [bibtex](#bibtex)

![RSS2020 H-ReIL overview](/images/rss2020-h-reil-1.jpg)

### Abstract

Autonomous driving has achieved significant progress in recent years, but autonomous cars are still unable to tackle high-risk situations where a potential accident is likely. In such near-accident scenarios, even a minor change in the vehicle's actions may result in drastically different consequences. To avoid unsafe actions in near-accident scenarios, we need to fully explore the environment. However, reinforcement learning (RL) and imitation learning (IL), two widely-used policy learning methods, cannot model rapid phase transitions and are not scalable to fully cover all the states. To address driving in near-accident scenarios, we propose a hierarchical reinforcement and imitation learning (H-ReIL) approach that consists of low-level policies learned by IL for discrete driving modes, and a high-level policy learned by RL that switches between different driving modes. Our approach exploits the advantages of both IL and RL by integrating them into a unified learning framework. Experimental results and user studies suggest our approach can achieve higher efficiency and safety compared to other methods. Analyses of the policies demonstrate our high-level policy appropriately switches between different low-level policies in near-accident driving situations.

### Video

#### RSS 2020 spotlight talk

{% include youtube_embed.html id="6iEi4PDLQ8w" %}

#### Supplementary video

{% include youtube_embed.html id="CY24zlC_HdI" %}

### Bibtex

    @inproceedings{cao2020reinforcement,
        title={Reinforcement Learning based Control of Imitative Policies
            for Near-Accident Driving},
        author={Cao, Zhangjie and Biyik, Erdem and Wang, Woodrow and Raventos, Allan and
            Gaidon, Adrien and Rosman, Guy and Sadigh, Dorsa},
        booktitle={Robotics: Science and Systems XVI},
        year={2020},
        month={Jul},
        url={http://dx.doi.org/10.15607/rss.2020.xvi.039},
        DOI={10.15607/rss.2020.xvi.039},
    }
