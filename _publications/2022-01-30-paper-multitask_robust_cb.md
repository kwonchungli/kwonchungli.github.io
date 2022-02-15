---
title: "Coordinate Attacks against Contextual Bandits: Fundamental Limits and Defense Mechanisms"
collection: arXiv
permalink: multitask_robust_cb
excerpt: 
date: 2022-01-30
paperurl: 'https://arxiv.org/abs/2201.12700'
citation: 
authors: <b>J. Kwon</b>, Y. Efroni, C. Caramanis and S. Mannor
publisher: Preprint, 2022
---

Motivated by online recommendation systems, we propose the problem of finding the optimal policy in multitask contextual bandits when a small fraction $\alpha < 1/2$ of tasks (users) are arbitrary and adversarial. The remaining fraction of good users share the same instance of contextual bandits with $S$ contexts and $A$ actions (items). Naturally, whether a user is good or adversarial is not known in advance. The goal is to robustly learn the policy that maximizes rewards for good users with as few user interactions as possible. Without adversarial users, established results in collaborative filtering show that $O(1/\epsilon^2)$ per-user interactions suffice to learn a good policy, precisely because information can be shared across users. This parallelization gain is fundamentally altered by the presence of adversarial users: unless there are super-polynomial number of users, we show a lower bound of $\tilde{\Omega}(\min(S,A) \cdot \alpha^2 / \epsilon^2)$ {\it per-user} interactions to learn an $\epsilon$-optimal policy for the good users. We then show we can achieve an $\tilde{O}(\min(S,A)\cdot \alpha/\epsilon^2)$ upper-bound, by employing efficient robust mean estimators for both uni-variate and high-dimensional random variables. We also show that this can be improved depending on the distributions of contexts.  

[[Arxiv]](https://arxiv.org/abs/2201.12700) 