---
title: "Distributionally Robust Policy Gradient for Offline Contextual Bandits"
collection: publications
permalink: /publication/Distributionally Robust Policy Gradient for Offline Contextual Bandits
excerpt: ''
date: 2023
venue: 'AISTATS'
citation: 'Zhouhao Yang, Yihong Guo, Pan Xu, Anqi Liu, Animashree Anandkumar Proceedings of The 26th International Conference on Artificial Intelligence and Statistics, PMLR 206:6443-6462, 2023.'
---
Abstract: Learning an optimal policy from offline data is notoriously challenging, which requires the evaluation of the learning policy using data pre-collected from a static logging policy. We study the policy optimization problem in offline contextual bandits using policy gradient methods. We employ a distributionally robust policy gradient method, DROPO, to account for the distributional shift between the static logging policy and the learning policy in policy gradient. Our approach conservatively estimates the conditional reward distributional and updates the policy accordingly. We show that our algorithm converges to a stationary point with rate O(1/T), where T is the number of time steps. We conduct experiments on real-world datasets under various scenarios of logging policies to compare our proposed algorithm with baseline methods in offline contextual bandits. We also propose a variant of our algorithm, DROPO-exp, to further improve the performance when a limited amount of online interaction is allowed. Our results demonstrate the effectiveness and robustness of the proposed algorithms, especially under heavily biased offline data.

[Download paper here](http://Zhouhao-Yang.github.io/files/yang23f.pdf)

Recommended citation: Zhouhao Yang, Yihong Guo, Pan Xu, Anqi Liu, Animashree Anandkumar Proceedings of The 26th International Conference on Artificial Intelligence and Statistics, PMLR 206:6443-6462, 2023.
