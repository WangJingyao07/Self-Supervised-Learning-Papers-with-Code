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
