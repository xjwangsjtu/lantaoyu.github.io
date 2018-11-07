---
title: "Large-scale Interactive Recommendation with Tree-structured Policy Gradient"
collection: publications
permalink: /publications/AAAI
venue: "AAAI 2019"
date: 2018-09-11
citation: 'Haokun Chen, Xinyi Dai, Weinan Zhang, Han Cai, <b>Xuejian Wang</b>, Ruiming Tang, Yuzhou Zhang, Yong Yu. <i> The Thirty-Third AAAI Conference on Artificial Intelligence </i> <b>AAAI 2019</b>.'
---  
[[PDF]](https://xjwangsjtu.github.io/_pages/404.md)

## Abstract
Reinforcement learning (RL) has recently been introduced to interactive recommender systems (IRS) because of its nature of learning from dynamic interactions and planning for long-run performance. As IRS is always with thousands of items and recommending an item is regarded as an action, most existing RL-based methods, however, fail to handle such a large discrete action space problem and thus become inefﬁcient. The existing work that tries to deal with the large discrete action space problem by utilizing the deep deterministic policy gradient framework suffers from the inconsistency between the continuous action representation (output from the actor network) and the real discrete actions. To avoid such inconsistency and achieve high efﬁciency and recommendation ef-fectiveness, in this paper, we propose a Tree-structured Policy Gradient Recommendation (TPGR) framework, where a balanced hierarchical clustering tree is built over the items and picking an item is formulated as seeking a path from the root to a certain leaf of the tree. Extensive experiments on carefully-designed environments based on two real-world datasets demonstrate that our model provides superior recommendation performance and signiﬁcant efﬁciency improvement over state-of-the-art methods.