---
title: "Behaviorally Diverse Traffic Simulation via Reinforcement Learning"
collection: publications
permalink: /publication/2020-10-25-Behaviorally-Diverse-Traffic-Simulation-via-RL
excerpt: "Reinforcement Learning of autonomous driving agent policies to balance driving skills and behavioral diversity."
date: 2020-10-25
venue: "IROS 2020"
venuetype: "conference"
paperauthors: 'S. Shiroshita, S. Maruyama, D. Nishiyama, M. Ynocente Castro, K. Hamzaoui, G. Rosman, J. DeCastro, KH. Lee, A. Gaidon'
thumbnail: "behaviorally-diverse-RL-teaser.jpg"
---

Links: [arxiv](https://arxiv.org/abs/2011.05741), [video](#video), [bibtex](#bibtex)

![Behaviorally Diverse RL](/images/behaviorally-diverse-RL.jpg)

### Abtract

Traffic simulators are important tools in autonomous driving development. While continuous progress has been made to provide developers more options for modeling various traffic participants, tuning these models to increase their behavioral diversity while maintaining quality is often very challenging. This paper introduces an easily-tunable policy generation algorithm for autonomous driving agents. The proposed algorithm balances diversity and driving skills by leveraging the representation and exploration abilities of deep reinforcement learning via a distinct policy set selector. Moreover, we present an algorithm utilizing intrinsic rewards to widen behavioral differences in the training. To provide quantitative assessments, we develop two trajectory-based evaluation metrics which measure the differences among policies and behavioral coverage. We experimentally show the effectiveness of our methods on several challenging intersection scenes.


### Video

{% include youtube_embed.html id="nxiBXHnCn0o" %}


### Bibtex

    @inproceedings{shiroshita2020behaviorally,
        title={Behaviorally Diverse Traffic Simulation via Reinforcement Learning},
        author={Shinya Shiroshita and Shirou Maruyama and Daisuke Nishiyama and Mario Ynocente Castro and Karim Hamzaoui and Guy Rosman and Jonathan DeCastro and Kuan-Hui Lee and Adrien Gaidon},
        booktitle={IROS},
        year={2020},
    }