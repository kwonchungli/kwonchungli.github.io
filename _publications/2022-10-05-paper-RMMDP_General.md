---
title: "Reward-Mixing MDPs with Few Latent Contexts are Learnable"
collection: arXiv
permalink: rmmdp_general
excerpt: 
date: 2022-10-05
paperurl: 'https://arxiv.org/abs/2210.02594'
citation: 
authors: <b>J. Kwon</b>, Y. Efroni, C. Caramanis and S. Mannor
publisher: Proceedings of the 40th International Conference on Machine Learning (ICML) 2023

---

We consider episodic reinforcement learning in reward-mixing Markov decision processes (RMMDPs): at the beginning of every episode nature randomly picks a latent reward model among M candidates and an agent interacts with the MDP throughout the episode for H time steps. Our goal is to learn a near-optimal policy that nearly maximizes the H time-step cumulative rewards in such a model. Previous work established an upper bound for RMMDPs for $M=2$. In this work, we resolve several open questions remained for the RMMDP model. For an arbitrary $M\ge2$, we provide a sample-efficient algorithm--EM2--that outputs an \epsilon-optimal policy using $O(\epsilon^{-2} \cdot S^d A^d \cdot poly(H,Z)^d )$ episodes, where S,A are the number of states and actions respectively, H is the time-horizon, Z is the support size of reward distributions and $d=\min(2M−1,H)$. Our technique is a higher-order extension of the method-of-moments based approach, nevertheless, the design and analysis of the \algname algorithm requires several new ideas beyond existing techniques. We also provide a lower bound of $(SA)^{\Omega{\sqrt{M}}/\epsilon^2$ for a general instance of RMMDP, supporting that super-polynomial sample complexity in M is necessary.


[[Arxiv]](https://arxiv.org/abs/2210.02594)