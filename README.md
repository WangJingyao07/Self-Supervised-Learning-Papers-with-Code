<div>
  <div align="right">
    👆 右上角点击 <img class="ai-header-badge-img" src="https://img.shields.io/github/stars/WangJingyao07/Self-Supervised-Learning-Papers-with-Code.svg?style=social&label=Star"> 告诉我，你希望这个项目继续加速更新迭代 ❤️ & ☕️
  </div>
</div>

# Self-supervised-Learning
自监督学习的项目与paper总结-Project and paper summary of self-supervised learning
【不断更新，2022.8.12构建仓库】

## SimCLR
- **A Simple Framework for Contrastive Learning of Visual Representations**

- **Paper**: http://proceedings.mlr.press/v119/chen20j.html

- **Pdf**: /simclr/A Simple Framework for Contrastive Learning of Visual Representations.pdf

- **Code**: https://github.com/google-research/simclr

- **Abstract**: 

This paper presents SimCLR: a simple framework for contrastive learning of visual representations. We simplify recently proposed contrastive selfsupervised learning algorithms without requiring specialized architectures or a memory bank. In order to understand what enables the contrastive prediction tasks to learn useful representations, we systematically study the major components of our framework. We show that (1) composition of data augmentations plays a critical role in defining effective predictive tasks, (2) introducing a learnable nonlinear transformation between the representation and the contrastive loss substantially improves the quality of the learned representations, and (3) contrastive learning benefits from larger batch sizes and more training steps compared to supervised learning. By combining these findings, we are able to considerably outperform previous methods for self-supervised and semi-supervised learning on ImageNet. A linear classifier trained on self-supervised representations learned by SimCLR achieves 76.5% top-1 accuracy, which is a 7% relative improvement over previous state-ofthe-art, matching the performance of a supervised ResNet-50. When fine-tuned on only 1% of the labels, we achieve 85.8% top-5 accuracy, outperforming AlexNet with 100× fewer labels.

![1660403672094](https://user-images.githubusercontent.com/110955859/184500227-37e98b1a-3c57-4c05-b4e2-76c3f2640cfe.png)

- **Related work**: based on SimCLR

- **Pdf**: /simclr/<br>

- [1] Speech simclr: Combining contrastive and reconstruction objective for self-supervised speech representation learning(https://arxiv.org/abs/2010.13991)<br>
- [2] Improved baselines with momentum contrastive learning (https://arxiv.org/abs/2003.04297)<br>
- [3] Semi-Supervising Learning, Transfer Learning, and Knowledge Distillation with SimCLR (https://arxiv.org/abs/2108.00587)<br>

## BYOL
- **Bootstrap Your Own Latent-a New Approach to Self-supervised Learning**

- **Paper**: [http://proceedings.mlr.press/v119/chen20j.html](https://proceedings.neurips.cc/paper/2020/hash/f3ada80d5c4ee70142b17b8192b2958e-Abstract.html)

- **Pdf**: /simclr/Bootstrap Your Own Latent-a New Approach to Self-supervised Learning.pdf

- **Code**: [https://github.com/google-research/simclr](https://github.com/deepmind/deepmind-research/tree/master/byol)

- **Abstract**: 

We introduce Bootstrap Your Own Latent (BYOL), a new approach to self-supervised image representation learning. BYOL relies on two neural networks, referred to as online and target networks, that interact and learn from each other. From an augmented view of an image, we train the online network to predict the target network representation of the same image under a different augmented view. At the same time, we update the target network with a slow-moving average of the online network. While state-of-the art methods intrinsically rely on negative pairs, BYOL achieves a new state of the art without them. BYOL reaches 74.3% top-1 classification accuracy on ImageNet using the standard linear evaluation protocol with a standard ResNet-50 architecture and 79.6% with a larger ResNet. We also show that BYOL performs on par or better than the current state of the art on both transfer and semi-supervised benchmarks.

![1660443412823](https://user-images.githubusercontent.com/110955859/184519725-a3c1c110-fd09-47f9-80db-647a8caa4347.png)


- **Related work**: based on BYOL

- **Pdf**: /byol/<br>

- [1] BYOL for audio: Self-supervised learning for general-purpose audio representation ([https://arxiv.org/abs/2010.13991](https://ieeexplore.ieee.org/abstract/document/9534474/))<br>
- [2] Run away from your teacher: Understanding byol by a novel self-supervised approach ([https://arxiv.org/abs/2003.04297](https://arxiv.org/abs/2011.10944))<br>



## Barlow Twins
- **Barlow Twins: Self-Supervised Learning via Redundancy Reduction**

- **Paper**: [[http://proceedings.mlr.press/v119/chen20j.html](https://proceedings.neurips.cc/paper/2020/hash/f3ada80d5c4ee70142b17b8192b2958e-Abstract.html)](http://proceedings.mlr.press/v139/zbontar21a.html)

- **Pdf**: /simclr/Barlow Twins_Self-Supervised Learning via Redundancy Reduction.pdf

- **Code**: [[https://github.com/google-research/simclr](https://github.com/deepmind/deepmind-research/tree/master/byol)](https://github.com/facebookresearch/barlowtwins)

- **Abstract**: 

Self-supervised learning (SSL) is rapidly closing the gap with supervised methods on large computer vision benchmarks. A successful approach to SSL is to learn embeddings which are invariant to distortions of the input sample. However, a recurring issue with this approach is the existence of trivial constant solutions. Most current methods avoid such solutions by careful implementation details. We propose an objective function that naturally avoids collapse by measuring the cross-correlation matrix between the outputs of two identical networks fed with distorted versions of a sample, and making it as close to the identity matrix as possible. This causes the embedding vectors of distorted versions of a sample to be similar, while minimizing the redundancy between the components of these vectors. The method is called Barlow Twins, owing to neuroscientist H. Barlow's redundancy-reduction principle applied to a pair of identical networks. Barlow Twins does not require large batches nor asymmetry between the network twins such as a predictor network, gradient stopping, or a moving average on the weight updates. Intriguingly it benefits from very high-dimensional output vectors. Barlow Twins outperforms previous methods on ImageNet for semi-supervised classification in the low-data regime, and is on par with current state of the art for ImageNet classification with a linear classifier head, and for transfer tasks of classification and object detection.

![1660443646285](https://user-images.githubusercontent.com/110955859/184519795-87bff4dc-d12b-4fd9-9443-e2d970d549cd.png)


- **Related work**: based on Barlow Twins

- **Pdf**: /barlow twins/<br>

- [1] A note on connecting barlow twins with negative-sample-free contrastive learning ([[https://arxiv.org/abs/2010.13991](https://ieeexplore.ieee.org/abstract/document/9534474/)](https://arxiv.org/abs/2104.13712))<br>
- [2] Graph Barlow Twins: A self-supervised representation learning framework for graphs ([[https://arxiv.org/abs/2003.04297](https://arxiv.org/abs/2011.10944)](https://arxiv.org/abs/2106.02466))<br>



## SimSam
- **Exploring Simple Siamese Representation Learning**

- **Paper**: [http://proceedings.mlr.press/v119/chen20j.html](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Exploring_Simple_Siamese_Representation_Learning_CVPR_2021_paper.html)

- **Pdf**: /simclr/Exploring Simple Siamese Representation Learning.pdf

- **Code**: [https://github.com/google-research/simclr](https://github.com/facebookresearch/simsiam)

- **Abstract**: 

Siamese networks have become a common structure in various recent models for unsupervised visual representation learning. These models maximize the similarity between two augmentations of one image, subject to certain conditions for avoiding collapsing solutions. In this paper, we report surprising empirical results that simple Siamese networks can learn meaningful representations even using none of the following: (i) negative sample pairs, (ii) large batches, (iii) momentum encoders. Our experiments show that collapsing solutions do exist for the loss and structure, but a stop-gradient operation plays an essential role in preventing collapsing. We provide a hypothesis on the implication of stop-gradient, and further show proof-of-concept experiments verifying it. Our "SimSiam" method achieves competitive results on ImageNet and downstream tasks. We hope this simple baseline will motivate people to rethink the roles of Siamese architectures for unsupervised representation learning. Code is made available. (https://github.com/facebookresearch/simsiam)


![1660443898001](https://user-images.githubusercontent.com/110955859/184519886-f923f2e9-6caf-4de0-9d4e-fa2541a83d12.png)

- **Related work**: based on SimSam

- **Pdf**: /simsam/<br>

- [1] Contrastive learning meets transfer learning_a case study in medical image analysis ([https://arxiv.org/abs/2010.13991](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12033/120332Q/Contrastive-learning-meets-transfer-learning--a-case-study-in/10.1117/12.2610990.short?SSO=1))<br>
- [2] How does simsiam avoid collapse without negative samples a unified understanding with self-supervised contrastive learning ([https://arxiv.org/abs/2003.04297](https://arxiv.org/abs/2203.16262))<br>
- [3] Simtriplet_Simple triplet representation learning with a single gpu ([https://arxiv.org/abs/2108.00587](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_10))<br>

