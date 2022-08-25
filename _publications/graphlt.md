---
title: "Deperturbation of Online Social Networks via Bayesian Label Transition"
collection: publications
permalink: /publications/graphlt
---

[[Paper]]([https://arxiv.org/abs/2010.14121](https://epubs.siam.org/doi/pdf/10.1137/1.9781611977172.68))

## Abstract
Online social networks (OSNs) classify users into different categories based on their online activities and interests, a task which is referred as a node classification task. Such a task can be solved effectively using Graph Convolutional Networks (GCNs). However, a small number of users, so-called perturbators, may perform random activities on an OSN, which significantly deteriorate the performance of a GCN-based node classification task. Existing works in this direction defend GCNs either by adversarial training or by identifying the attacker nodes followed by their removal. However, both of these approaches require that the attack patterns or attacker nodes be identified first, which is difficult in the scenario when the number of perturbator nodes is very small. In this work, we develop a GCN defense model, namely GraphLT, which uses the concept of label transition. GraphLT assumes that perturbators' random activities deteriorate GCN's performance. To overcome this issue, GraphLT subsequently uses a novel Bayesian label transition model, which takes GCN's predicted labels and applies label transitions by Gibbs-sampling-based inference and thus repairs GCN's prediction to achieve better node classification. Extensive experiments on seven benchmark datasets show that GraphLT considerably enhances the performance of the node classifier in an unperturbed environment; furthermore, it validates that GraphLT can successfully repair a GCN-based node classifier with superior performance than several competing methods.

<p align="center">
  <img src="/images/pub_img/fig_graphlt.png?raw=true" style="width: 700px;"/> 
</p>

## Citation
```
@inproceedings{zhuang2022deperturbation,
  title={Deperturbation of Online Social Networks via Bayesian Label Transition},
  author={Zhuang, Jun and Al Hasan, Mohammad},
  booktitle={Proceedings of the 2022 SIAM International Conference on Data Mining (SDM)},
  pages={603--611},
  year={2022},
  organization={SIAM}
}
```
