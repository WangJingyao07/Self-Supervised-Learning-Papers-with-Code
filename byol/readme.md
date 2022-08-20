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
