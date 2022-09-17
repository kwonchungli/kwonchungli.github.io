---
title: "Tractable Optimality in Episodic Latent MABs"
collection: arXiv
permalink: lmab
excerpt: 
date: 2022-09-14
paperurl: ''
paperconf: ''
citation: 
authors: <b>J. Kwon</b>, Y. Efroni, C. Caramanis and S. Mannor
publisher: Proceedings of the 36th Neural Information Processing Systems (NeurIPS) 2022 (to appear)
---

We consider a multi-armed bandit problem with $A$ actions and $M$ latent contexts, where an agent interacts with the environment for an episode of $H$ time steps. Depending on the length of the episode, the learner may not be able to estimate accurately the latent context. The resulting partial observation of the environment makes the learning task significantly more challenging. 
Without any additional structural assumptions, existing techniques to tackle partially observed settings imply the decision maker can learn a near-optimal policy with $O(A)^H$ episodes, but do not promise more. 
In this work, we show that learning with {\em polynomial} samples in $A$ is possible. We achieve this by using techniques from experiment design. Then, through a method-of-moments approach, we design a procedure that provably learns a near-optimal policy with $O(\poly(A) + \poly(M,H)^{\min(M,H)})$ interactions. In practice, we show that we can formulate the moment-matching via maximum likelihood estimation. In our experiments, this significantly outperforms the worst-case guarantees, as well as existing practical methods.


[[Arxiv]](.)