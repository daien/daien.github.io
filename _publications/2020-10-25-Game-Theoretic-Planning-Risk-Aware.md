---
title: "Game-Theoretic Planning for Risk-Aware Interactive Agents"
collection: publications
permalink: /publication/2020-10-25-Game-Theoretic-Planning-Risk-Aware
excerpt: "A risk-sensitive game-theoretic control algorithm to model complex multi-agent interactions yielding more time-efficient, intuitive, and safe behaviors when facing underlying risks and uncertainty."
date: 2020-10-25
venue: "IROS 2020"
venuetype: "conference"
paperauthors: 'M. Wang, N. Mehr, A. Gaidon, M. Schwager'
thumbnail: "leq-game.jpg"
---

Links: [pdf](/files/2020_IROS_leq_game.pdf), [video](#video), [bibtex](#bibtex)

![LEQ Game](/images/leq-game.jpg)

### Abtract

Modeling the stochastic behavior of interacting agents is key for safe motion planning. In this paper, we study the interaction of risk-aware agents in a game-theoretical framework. Under the entropic risk measure, we derive an iterative algorithm for approximating the intractable feedback Nash equilibria of a risk-sensitive dynamic game. We use an iteratively linearized approximation of the system dynamics and a quadratic approximation of the cost function in solving a backward recursion for finding feedback Nash equilibria. In this respect, the algorithm shares a similar structure with DDP and iLQR methods. We conduct experiments in a set of challenging scenarios such as roundabouts. Compared to ignoring the game interaction or the risk sensitivity, we show that our risk-sensitive game-theoretic framework leads to more time-efficient, intuitive, and safe behaviors when facing underlying risks and uncertainty.

### Video

{% include youtube_embed.html id="kbeaPIWqrsE" %}

### Bibtex

    @inproceedings{wang2020game,
        title={Game-Theoretic Planning for Risk-Aware Interactive Agents},
        author={Mingyu Wang and Negar Mehr and Adrien Gaidon and Mac Schwager},
        booktitle={IROS},
        year={2020},
    }