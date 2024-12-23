---
title: 'ELIZA Bonini and How to Avoid the o737 Max Crash'
date: 2024-12-22
permalink: /posts/2024/12/eliza/
tags:
  - misc
---

The amazing results of [OpenAI's o3](https://community.openai.com/t/day-12-of-shipmas-new-frontier-models-o3-and-o3-mini-announcement/1061818) got everybody thinking deeply about the future, again. [Brad Porter](https://www.linkedin.com/in/brad-porter-1a989/) (CEO of [CoBot](https://www.co.bot/), one of our portfolio companies at [Calibrate Ventures](https://www.calibratevc.com/) for full disclosure) reposted his essay ["Approaching the AGI Asymptote"](https://medium.com/@bp_64302/approaching-the-agi-asymptote-5f1737a0033f) and re-analyzed his conclusions in this [linkedin post](https://www.linkedin.com/posts/brad-porter-1a989_approaching-the-agi-asymptote-activity-7276619030092783616-tm8L/). Brad is a prolific writer that always has me thinking deeply, so I strongly recommend reading those posts!

The main points Brad made at the time were about:
1) how do we know we are approaching AGI ("the more convoluted the arguments distinguishing machine from human intelligence become, the closer we actually are to artificial general intelligence"),
2) who gets to say if we need to worry or not (more than just AI luminaries, which was echoed recently as "let's stop deferring to insiders" in this [excellent "AI snake oil" blog](https://www.aisnakeoil.com/p/is-ai-progress-slowing-down) by hype sharpshooter Arvind Narayanan),
3) an AI Safety framework based around ethical considerations of ever more capable AIs.

Brad re-analyzed his thinking and largely stood by it, with some caveats (again, go read his post!). Brad then asked what do we think? I normally just keep these kind of thoughts to my inner circle, but it's an unusually rainy Sunday morning in California, and everyone at home is still asleep... So I went a bit deeper than usual, and jotted down some of my AI safety thoughts that had been crystallizing for a while.

My position is nuanced (as indicated by the length of this post, which I feel is still too short), but in a nutshell:
1) progress cannot and should not be stopped, but we need to be extra careful,
2) to do so, and based on my personal experience in autonomous driving and robotics, we should be wary of anthropomorphism and lean more into functional safety while emphasizing human responsibility.

Now what does this have to do with the title of this post, who is Eliza Bonini and what is the o737 Max? Read on ;-)

![ELIZA Bonini and how to avoid the o737 Max crash (made with Whisk)](/images/eliza-bonini-AI-turtles-o737max-whisk.jpg "ELIZA Bonini and how to avoid the o737 Max crash (made with Whisk)")

# Bonini's Paradox

First of all, ELIZA Bonini is not a real person (or maybe it is, but that would be unintentional). I use this for comedic effect to describe the conjunction of two ideas latent in Brad's essay and present in much of the commentary on AI throughout history: **Bonini's paradox** and the **ELIZA effect**.

Brad's definition of the AGI asymptote reminded me of [Bonini's paradox](https://en.wikipedia.org/wiki/Bonini%27s_paradox) and, pardon my French, Paul Valéry's elegant quote: "Ce qui est simple est toujours faux. Ce qui ne l’est pas est inutilisable". ("What is simple is always false. What is not is unusable.") As stated in the article above, Bonini's paradox is: "As a model of a complex system becomes more complete, it becomes less understandable. Alternatively, **as a model grows more realistic, it also becomes just as difficult to understand as the real-world processes it represents**."

This paradox, grounded in the famous ["no free lunch" theorems](https://en.wikipedia.org/wiki/No_free_lunch_theorem), is often discussed across sci-fi literature (e.g., in Asimov's Foundation series), developers of simulation tools (e.g., the resources needed to build and run "world models", a very hot topic in AI startups like [Runway](https://runwayml.com/research/introducing-general-world-models), [World Labs](https://www.worldlabs.ai/blog), [Odyssey](https://odyssey.systems/introducing-explorer), or [Wayve](https://wayve.ai/science/gaia/)), as well as [neural scaling laws](https://en.wikipedia.org/wiki/Neural_scaling_law) and the galloping capital and energy needs of AI datacenters (e.g., [Meta's 2GW Louisiana one](https://www.datacenterdynamics.com/en/news/meta-announces-4-million-sq-ft-louisiana-data-center-campus/)).

At a technical level, Bonini's paradox is becoming a central concept in LLMs now that there is a scalable path towards what some might call ever more complex "reasoning" (the inference-time scaling techniques used in o3 for instance). Normally, it is much easier to verify a solution than to find it (in an echo of the good old P vs NP problem), but **evaluation of sophisticated AI models like o3 is becoming extremely challenging**. Few benchmarks are as good as ARC-AGI, and we are kind of saturating them all. Hence, we are increasingly leveraging AI to evaluate itself (LLMs as judge and other techniques, as mentioned in the aforementioned [o3 announcement video](https://community.openai.com/t/day-12-of-shipmas-new-frontier-models-o3-and-o3-mini-announcement/1061818)).

Thus, **the growing complexity of these systems is escaping our understanding of their capabilities** (let alone their inner workings). That's just a fact, and the cat is out of the bag. I don't think we can put it back, nor do I personally want to (yes, I'm a cat person). It's just too useful and exciting! But, not to go Uncle-Ben-y, with great power comes great responsibility (ok, I did go Uncle Ben, sorry).

So how are we going to mitigate the risks of ever-more capable, and hence inscrutable, AI? What are even the risks?


# The ELIZA Effect

As I was classically trained in philosophy in France, I would need to start by defining rigorously foggy concepts like "AGI", but this is beyond the scope of this blog. Instead, I will focus on Brad's definition of the aforementioned "AGI asymptote" in terms of the distance w.r.t. human explanations. This definition seems to elegantly address Bonini's paradox by mapping to human behavior (e.g., a tendency towards mysticism in our explanations of phenomena that transcend our understanding), something we can observe and measure and test, thus scientific!

However, in my humble opinion, the ensuing AI safety framework sometimes teeters on the edge of **the anthropomorphization trap**. This is where ELIZA finally comes into the picture.

The [ELIZA effect](https://en.wikipedia.org/wiki/ELIZA_effect) is **a tendency to project human traits onto interactive computer programs**. The effect is named for [ELIZA](https://en.wikipedia.org/wiki/ELIZA), the 1966 chatbot developed by MIT computer scientist Joseph Weizenbaum, and something I personally learned about from my friend and mentor Gill Pratt.

We are a lightyears ahead of ELIZA (the chatbot) now with incredible technology like GPT-4 and o3, so the ELIZA effect is more prevalent than ever. However, the illusion it creates is much more impactful now, especially when it comes to safety. **The ELIZA effect indeed tends to overemphasize anthropomorphic safety concepts vs functional ones**. Moral goodness, intentions, fear, etc are all human concepts. They relate to organizational or regulatory constraints on *people*, developers and users, more than implementation details (cf. the SB1047 debate). **We regulate moral entities, people, not AIs.** An AI (or a self-driving car for that matter) cannot kill someone and go to jail. The users or developers of these tools can.

At a technical level, the ELIZA effect is even more potent now, as the progress in AI is largely rooted in imitation learning. **Anthropomorphization *is* an effective technique** for users to squeeze the most juice out of LLMs (including jailbreaking!), because it projects inputs closer to the training data (all of them: pretraining, SFT, RLHF). Same for developers, for instance with the latest progress in inference-time scaling and chain of thought. Statistical alignment to avoid out-of-domain generalization issues is essentially what prompt engineering does (cf. [Subbarao Kambhampati](https://x.com/rao2z) for interesting posts on these topics). The heart of ML remains unchanged in my mind: it is the i.i.d. assumption (data are independent and identically distributed).


# Safety is an Engineering Problem

So what if we anthropomorphize AI too much? From my perspective building ML-heavy autonomous driving and robotic systems, **the ELIZA effect hurts on both ends: it slows down adoption by skeptics and creates real engineering pitfalls for trailblazers by creating philosophical distractions**. Those are the real harms of the anthropomorphization of AI. If I learned one thing from Autonomous Driving, it is that **safety is about engineering, not philosophy**.

(As a side note, what's funny to me is my own reversal of attitude over the years as I deployed more and more of my initially crazy research ideas (e.g., around sim-to-real transfer, end-to-end learning, and self-supervised learning). I went into AI almost 20 years ago for philosophical reasons, but stayed because of the [unreasonable effectiveness of mathematics](https://en.wikipedia.org/wiki/The_Unreasonable_Effectiveness_of_Mathematics_in_the_Natural_Sciences) and engineering 😉)

At the heart of safety engineering, **Functional Safety** needs to be taken extremely seriously to minimize the risks of catastrophic failures in complex safety-critical systems (LLMs have gotten good enough to fit that category in my book). **We don't want any doors to blow up mid-flight when the o737 Max (a.k.a. AGI, the grand-grand-grand-grand-...-child of o3) takes off!** Functional Safety experts are key to making extremely capable AI systems safely deployable. I personally learned a lot from folks like Sagar Behere and his team in the early days of TRI. Brad's article discusses this (e.g., around access controls, which in AVs relate to Operational Design Domain, ODD), but sometimes with terms that are a bit too anthropomorphic or philosophical to my ears (e.g., around ethics and intent).


# From the Age of Training to the Age of Testing

Of course, AI practitioners like Brad and many others have incredibly complex and thorough testing, verification, validation, and CI/CD systems. However, the ELIZA effect is so strong now that many non-practitioners (e.g., non-technical CEOs) might think that AI Safety is primarily a philosophical issue, and thus might dangerously underinvest in safety engineering. **As the productivity of the builders keeps skyrocketing by recursively leveraging the tools they build, so must the productivity of safety engineers**.

Moreover, using the same tools as the builders is not enough for the testers (cf. the limits of LLMs as judges). **The ratio of tester-to-trainer abilities must grow superlinearly** due to the current "Field of Dreams" approach to testing ("just build it, testers will come") and the fundamental asymmetry of the costs: failing to build a better system is ok, failing to gate a catastrophically bad release is not. Testers must anticipate and move to where the puck is going, not where it stands.

This is why **we need to move from the age of training to the age of testing**. In data-centric ML terms, the test sets need to eventually dwarf the training sets. We are very far from that today. We are talking tens of trillions of tokens on the training side vs mere millions on the test side: that is **a 7 orders of magnitude difference**! Testing in public obviously has limits as the capabilities of the systems continue to scale. That's why simulation is so important in driving and robotics or Embodied AI in general. We need more safety engineering solutions like that for "AGI".


# Humans at the wheel

I don't want to completely disregard philosophical and ethical considerations of course. Maths and engineering are great, and everyone should invest way more into testing as outlined above. But that is not enough. AIs can't do all the jobs -- judge, jury, and executioner. It is not turtles, huh sorry AIs, all the way down. Ultimately, there are people at the bottom.
A quote I really like from one of my favorite books of all time, ["Creativity Inc."](https://en.wikipedia.org/wiki/Creativity,_Inc.) by Pixar founder Ed Catmull (one of the few management books applicable to research teams): **“Ideas come from people. Therefore, people are more important than ideas.”**

Humans are responsible and should be held accountable. In AI we talk a lot about "human in the loop" systems, scalable oversight, etc. But with the loops themselves becoming increasingly faster and more complex (and thus inscrutable per Bonini), the only scalable concepts are responsibility and accountability *of humans* (precision warranted to not fall for ELIZA again). Even if we use AI to help ourselves govern ever more powerful AI and it feels like turtles all the way down (e.g., with inscrutable chain of thoughts and [scary hints of recursive self-improvement loops](https://x.com/aisafetymemes/status/1870490131553194340?s=46)), in the end, our human hands are on the wheel, no matter how much horsepower there is under the hood. **In practice, *someone* has to actually *ask* (i.e. program) the AI to improve itself.** That person is responsible and accountable. There is power in the "maybe not" (for recursive self-improvement) remark by Sam Altman at the end of the o3 video. That would make for a great climbing t-shirt by the way.

![Maybe Not](/images/maybe-not-whisk.jpg "Maybe Not shirt (made with whisk).")


Furthermore, we can expect, and in fact demand, this level of accountability, because no matter what happens at the model level, the model itself is just a small part of a complex system (as I discussed in [my recent comment](https://x.com/adnothing/status/1869846739412529391?s=46) to the aforementioned "AI snake oil" blog of Arvind Narayanan *et al*). That ML system is itself part of a product with a specific purpose, set itself by a company, which is composed of accountable people, from developers to leaders. **It's people all the way down.**


# Conclusion

Obviously, if you've read this far, this post went way beyond just commenting on Brad's initial post. I completely fell hook, line, and sinker for his intellectually stimulating questions on the slippery slope of AI safety. Well done, Brad.

But now you know who ELIZA Bonini isn't, and might appreciate more deeply the pitfalls of anthropomorphization and the need for safety engineering, scaling up testing, and increased human accountability as o737 Max is preparing to take-off (extrapolating based on OpenAI's legendary naming sense 😉).

What about the argument that this might stifle progress? Not slowing down progress was important while we didn't know if it was possible to get this far, but now… things might be different (o3 is super impressive). **You don't need a speed limit when all cars can only go at 30km/h, but you do when they can go at more than 100km/h.** Note that you can still go as fast as you want on a race track or a crazy German Autobahn, but you can't in a school zone. What is the equivalent for AI? Good question 😉

**More rigorous safety engineering and accountability might actually be important not just to *survive* but to *win* in the long term**, as evidenced by the state of the autonomous vehicle industry. The best AV companies are indeed the ones that hired and empowered Functional Safety experts and publicly and transparently committed to safety engineering with a high degree of accountability. Considering the success of this approach in AVs, especially Waymo's, the industry leader in both commercial deployment *and* safety (cf. [Waymo's thorough approach to safety](https://waymo.com/safety/)), I hope to see more of that in AI broadly, both in terms of implementation, public discourse, and accountability.

What do you think? Please let me know on [twitter]() or [linkedin]().
And remember, it’s not turtles (or AIs) all the way down: ultimately, there is always a human at the wheel.

![The human at the wheel of the truck barreling towards AGI](/images/AGI-o737-dall-e.jpeg "The human at the wheel of the truck barreling towards AGI.")
