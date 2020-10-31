---
title: "Anti-perturbation of Online Social Networks by Graph Label Transition"
collection: publications
permalink: /publications/graphlt
---

[[Paper]](https://arxiv.org/abs/2010.14121)

## Abstract
Numerous popular online social networks (OSN) would classify users into different categories and recommend users to each other with similar interests. 
A small number of users, so-called perturbators, may perform some types of behaviors, which significantly disturb such an OSN classifier. 
Manual annotation by OSN administrators is one kind of potential solutions. 
However, the manual annotation unavoidably brings into noise. Besides, such perturbators are not Sybil users, and therefore their accounts cannot be frozen. 
To improve the robustness of such an OSN classifier, we generalize this issue as the defense of Graph Convolutional Networks (GCNs) on the node classification task. 
Most existing defenses on this task can be divided into the adversarial-based method and the detection-based method. 
The adversarial-based method improves the robustness of GCNs by training with adversarial samples. 
However, in our case, the perturbators are hard to be distinguished by OSN administrators and thus we cannot use adversarial samples in the training phase. 
By contrast, the detection-based method aims at detecting the attacker nodes or edges and alleviates the negative impact by removing them. 
In our scenario, nevertheless, the perturbators are not the attacker and thus cannot be eliminated. 
Both methods could not solve the aforementioned problems. 
To address these issues, we propose a novel graph label transition model, named GraphLT, to improve the robustness of the OSN classifier by transiting the node latent representation based on dynamic conditional label transition. 
Extensive experiments demonstrate that GraphLT can not only considerably enhance the performance of the node classifier in a clean environment but also successfully remedy the classifier with superior performance over competing methods on seven benchmark datasets after graph perturbation.

<p align="center">
  <img src="/images/pub_img/fig_graphlt.png?raw=true" style="width: 700px;"/> 
</p>

## Citation
@inproceedings{zhuang2020anti, <br>
  title={Anti-perturbation of Online Social Networks by Graph Label Transition}, <br>
  author={Zhuang, Jun and Al Hasan, Mohammad}, <br>
  journal={arXiv preprint arXiv:2010.14121}, <br>
  year={2020} <br>
}
