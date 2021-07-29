---
title: "Non-Exhaustive Learning Using Gaussian Mixture Generative Adversarial Networks"
collection: publications
permalink: /publications/negmgan
---

[[Paper]](https://2021.ecmlpkdd.org/wp-content/uploads/2021/07/sub_191.pdf)

## Abstract
Supervised learning, while deployed in real-life scenarios, often encounters instances of unknown classes. Conventional algorithms for training a supervised learning model do not provide an option to detect such instances, so they miss-classify such instances with 100% probability. Open Set Recognition (OSR) and Non-Exhaustive Learning (NEL) are potential solutions to overcome this problem. Most existing methods of OSR first classify members of existing classes and then identify instances of new classes. However, many of the existing methods of OSR only makes a binary decision, i.e., they only identify the existence of the unknown class. Hence, such methods cannot distinguish test instances belonging to incremental unseen classes. On the other hand, the majority of NEL methods often make a parametric assumption over the data distribution, which either fail to return good results, due to the reason that real-life complex datasets may not follow a well-known data distribution. In this paper, we propose a new online non-exhaustive learning model, namely, Non-Exhaustive Gaussian Mixture Generative Adversarial Networks (NE-GM-GAN) to address these issues. Our proposed model synthesizes Gaussian mixture based latent representation over a deep generative model, such as GAN, for incremental detection of instances of emerging classes in the test data. Extensive experimental results on several benchmark datasets show that NE-GM-GAN significantly outperforms the state-of-the-art methods in detecting instances of novel classes in streaming data.

<p align="center">
  <img src="/images/pub_img/fig_negmgan.png?raw=true" style="width: 500px;"/> 
</p>

## Citation
@inproceedings{zhuang2021non,  <br>
  title={Non-Exhaustive Learning Using Gaussian Mixture Generative Adversarial Networks},  <br>
  author={Zhuang, Jun and Hasan, Mohammad Al},  <br>
  journal={Proceedings of the ECML/PKDD},  <br>
  year={2021}  <br>
}
