---
title: "Lighter U-net for segmenting white matter hyperintensities in MR images"
collection: publications
permalink: /publications/lighter_unet
---

[[Paper]](https://dl.acm.org/doi/10.1145/3360774.3368203)

## Abstract
White matter hyperintensities (WMH) is one of main consequences of small vessel diseases. 
Automated WMH segmentation techniques play an important role in clinical research and practice. 
U-Net has been demonstrated to yield the best precise segmentation results so far. 
However, sometimes it losses more detailed information as network goes deeper. 
In addition, it usually depends on data augmentation or a large number of filters. 
Large filters increase the complexity of model, which may be an obstacle for real-time segmentation on cloud computing. 
To solve these two issues, a new architecture, Lighter U-Net is proposed to reinforce feature use, to reduce the number of parameters as well as to retain sufficient receptive fields without losing resolution. 
The extensive experiments suggest that the proposed network achieves comparable performance as the state-of-the-art methods by only using 17% parameters of standard U-Net.

<p align="center">
  <img src="/images/pub_img/fig_lighter_unet.png?raw=true" style="width: 500px;"/> 
</p>

## Citation
@inproceedings{zhuang2019lighter, <br>
  title={Lighter U-net for segmenting white matter hyperintensities in MR images}, <br>
  author={Zhuang, Jun and Gao, Mingchen and Al Hasan, Mohammad}, <br>
  booktitle={Proceedings of the 16th EAI International Conference on Mobile and Ubiquitous Systems: Computing, Networking and Services}, <br>
  pages={535--539}, <br>
  year={2019} <br>
}
