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
