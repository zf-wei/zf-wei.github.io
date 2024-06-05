---
title: "Robustness of graph embedding methods for community detection"
collection: publications
permalink: /publication/robustness
excerpt: 'The arXiv page: [here](https://arxiv.org/abs/2405.00636).'
date: 2024-05-15
venue: 'arXiv:2405.00636'
---

This work is joint with [Pablo Moriano](https://pmoriano.com/) and [Ramakrishnan Kannan](https://ramkikannan.com) during my internship at Oak Ridge National Laboratory. The arXiv page is [here](https://arxiv.org/abs/2405.00636).

## Abstract

This study investigates the robustness of graph embedding methods for  community detection in the face of network perturbations, specifically  edge deletions. Graph embedding techniques, which represent nodes as  low-dimensional vectors, are widely used for various graph machine  learning tasks due to their ability to capture structural properties of  networks effectively. However, the impact of perturbations on the  performance of these methods remains relatively understudied. The  research considers state-of-the-art graph embedding methods from two  families: matrix factorization (e.g., LE, LLE, HOPE, M-NMF) and random  walk-based (e.g., DeepWalk, LINE, node2vec). Through experiments  conducted on both synthetic and real-world networks, the study reveals  varying degrees of robustness within each family of graph embedding  methods. The robustness is found to be influenced by factors such as  network size, initial community partition strength, and the type of  perturbation. Notably, node2vec and LLE consistently demonstrate higher  robustness for community detection across different scenarios, including networks with degree and community size heterogeneity. These findings  highlight the importance of selecting an appropriate graph embedding  method based on the specific characteristics of the network and the task at hand, particularly in scenarios where robustness to perturbations is crucial.    