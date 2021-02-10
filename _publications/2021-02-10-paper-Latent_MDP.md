---
title: "RL for Latent MDPs: Regret Guarantees and a Lower Bound"
collection: arXiv
permalink: latent_mdp
excerpt: 
date: 2021-02-10
paperurl: 'https://arxiv.org/abs/2102.04939'
citation: 
authors: <b>J. Kwon</b>, Y. Efroni, C. Caramanis and S. Mannor
publisher: Working Paper
---

In this work, we consider the regret minimization problem for reinforcement learning in latent Markov Decision Processes (LMDP). In an LMDP, an MDP is randomly drawn from a set of $M$ possible MDPs at the beginning of the interaction, but the identity of the chosen MDP is not revealed to the agent. We first show that a general instance of LMDPs requires at least $\Omega((SA)^M)$ episodes to even approximate the optimal policy. Then, we consider sufficient assumptions under which learning good policies requires polynomial number of episodes. We show that the key link is a notion of separation between the MDP system dynamics. With sufficient separation, we provide an efficient algorithm with local guarantee, {\it i.e.,} providing a sublinear regret guarantee when we are given a good initialization. 


[[Arxiv]](https://arxiv.org/abs/2102.04939)