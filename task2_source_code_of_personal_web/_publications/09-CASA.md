---
title: "CASA-B: A Unified Framework of Model-Free Reinforcement Learning"
collection: publication
permalink: /publication/2021/05/09-CASA
excerpt: ' Building on the breakthrough of reinforcement learning, this paper introduces a unified framework of model-free reinforcement learning, CASA-B, Critic AS an Actor with Bandits Vote Algorithm. CASA-B is an actor-critic framework that estimates state-value, state-action-value and policy. An expectation-correct Doubly Robust Trace is introduced to learn state-value and state-action-value, whose convergence properties are guaranteed.'
date: 2021/05/09
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2105.03923'
citation: 'Xiao, C., Shi, H., Fan, J., &amp; Deng, S. (2021). CASA-B: A Unified Framework of Model-Free Reinforcement Learning. arXiv preprint arXiv:2105.03923.'
---

<a href='https://arxiv.org/abs/2105.03923'>Download PDF here</a>

Abstract: Building on the breakthrough of reinforcement learning, this paper introduces a unified framework of model-free reinforcement learning, CASA-B, Critic AS an Actor with Bandits Vote Algorithm. CASA-B is an actor-critic framework that estimates state-value, state-action-value and policy. An expectation-correct Doubly Robust Trace is introduced to learn state-value and state-action-value, whose convergence properties are guaranteed. We prove that CASA-B integrates a consistent path for the policy evaluation and the policy improvement. The policy evaluation is equivalent to a compensational policy improvement, which alleviates the function approximation error, and is also equivalent to an entropy-regularized policy improvement, which prevents the policy from collapsing to a suboptimal solution. Building on this design, we find the entropy of the behavior policies&apos; and the target policy&apos;s are disentangled. Based on this observation, we propose a progressive closed-form entropy control mechanism, which explicitly controls the behavior policies&apos; entropy to arbitrary range. Our experiments show that CASAB is super sample efficient and achieves State-Of-The-Art on Arcade Learning Environment. Our mean Human Normalized Score is 6456.63% and our median Human Normalized Score is 477.17%, under 200M training scale.

 Recommended citation: Xiao, C., Shi, H., Fan, J., & Deng, S. (2021). CASA-B: A Unified Framework of Model-Free Reinforcement Learning. arXiv preprint arXiv:2105.03923.