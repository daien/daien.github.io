---
title: "Discovering Avoidable Planner Failures of Autonomous Vehicles using Counterfactual Analysis in Behaviorally Diverse Simulation"
collection: publications
permalink: /publication/2020-09-20-Discovering-Avoidable-Planner-Failures
excerpt: "A method to automatically find planner-specific defects of autonomous vehicles in simulation."
date: 2020-09-20
venue: "ITSC 2020"
venuetype: "conference"
paperauthors: 'D. Nishiyama, M. Ynocente Castro, S. Maruyama, S. Shiroshita, K. Hamzaoui, Y. Ouyang, G. Rosman, J. DeCastro, KH. Lee, A. Gaidon'
thumbnail: "planner-failures-teaser.jpg"
---

Links: [arxiv](https://arxiv.org/abs/2011.11991), [bibtex](#bibtex)

![Planner failure collision angles](/images/planner-failures-angles.jpg)

### Abtract

Automated Vehicles require exhaustive testing in simulation to detect as many safety-critical failures as possible before deployment on public roads. In this work, we focus on the core decision-making component of autonomous robots: their planning algorithm. We introduce a planner testing framework that leverages recent progress in simulating behaviorally diverse traffic participants. Using large scale search, we generate, detect, and characterize dynamic scenarios leading to collisions. In particular, we propose methods to distinguish between unavoidable and avoidable accidents, focusing especially on automatically finding planner-specific defects that must be corrected before deployment. Through experiments in complex multi-agent intersection scenarios, we show that our method can indeed find a wide range of critical planner failures.

### Bibtex

    @inproceedings{nishiyama2020discovering,
        title={Discovering Avoidable Planner Failures of Autonomous Vehicles using Counterfactual Analysis in Behaviorally Diverse Simulation},
        author={Daisuke Nishiyama and Mario Ynocente Castro and Shirou Maruyama and Shinya Shiroshita and Karim Hamzaoui and Yi Ouyang and Guy Rosman and Jonathan DeCastro and Kuan-Hui Lee and Adrien Gaidon},
        booktitle={ITSC},
        year={2020},
    }