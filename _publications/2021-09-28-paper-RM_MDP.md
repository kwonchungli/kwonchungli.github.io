---
title: "Reinforcement Learning in Reward-Mixing MDPs"
collection: arXiv
permalink: rm_mdp
excerpt: 
date: 2021-09-28
paperurl: 'https://arxiv.org/abs/2110.03743'
paperconf: 'https://papers.nips.cc/paper/2021/hash/11f9e78e4899a78dedd439fc583b6693-Abstract.html'
citation: 
authors: <b>J. Kwon</b>, Y. Efroni, C. Caramanis and S. Mannor
publisher: Proceedings of the 35th Neural Information Processing Systems (NeurIPS) 2021
---

Learning a near optimal policy in a partially observable system remains an elusive challenge in contemporary reinforcement learning. In this work, we consider episodic reinforcement learning in a reward-mixing Markov decision process (MDP). There, a reward function is drawn from one of $M$ possible reward models at the beginning of every episode, but the identity of the chosen reward model is not revealed to the agent. Hence, the latent state space, for which the dynamics are Markovian, is not given to the agent. We study the problem of learning a near optimal policy for two reward-mixing MDPs. Unlike existing approaches that rely on strong assumptions on the dynamics, we make no assumptions and study the problem in full generality. Indeed, with no further assumptions, even for two switching reward-models, the problem requires several new ideas beyond existing algorithmic and analysis techniques for efficient exploration. We provide the first polynomial-time algorithm that finds an $\epsilon$-optimal policy after exploring $\tilde{O}(poly(H,\epsilon^{-1}) \cdot S^2 A^2)$ episodes, where $H$ is time-horizon and $S, A$ are the number of states and actions respectively. This is the first efficient algorithm that does not require any assumptions in partially observed environments where the observation space is smaller than the latent state space. 


[[Arxiv]](https://arxiv.org/abs/2110.03743) [[Conference]](https://papers.nips.cc/paper/2021/hash/11f9e78e4899a78dedd439fc583b6693-Abstract.html)