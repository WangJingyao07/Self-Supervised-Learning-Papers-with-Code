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
