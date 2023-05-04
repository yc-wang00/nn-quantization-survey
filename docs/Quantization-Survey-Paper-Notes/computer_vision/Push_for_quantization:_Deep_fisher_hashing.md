# Push for quantization: Deep fisher hashing

## Summary

<Summary: >The paper explores the use of discrete binary codes for efficient storage and processing of high-dimensional data, and how deep learning methods can be optimized for image hashing using gradient-based methods. The authors introduce a margin on distances between dissimilar image pairs and maximize binary distances between classes while minimizing binary distance within the same class (inspired by Fisher LDA) to optimize maximum class separability in binary space. Experiments on CIFAR-10, NUS-WIDE and ImageNet100 show that the proposed method yields compact codes that compare favorably to the current state of the art.


## Target Task

computer vision

## Content

<Abstract: >Current massive datasets demand light-weight access for analysis. Discrete hashing methods are thus beneﬁcial because they map high-dimensional data to compact binary codes that are efﬁcient to store and process, while preserving semantic similarity. To optimize powerful deep learning methods for image hashing, gradient-based methods are required. Binary codes, however, are discrete and thus have no continuous derivatives. Relaxing the problem by solving it in a continuous space and then quantizing the solution is not guaranteed to yield separable binary codes. The quantization needs to be included in the optimization. In this paper we push for quantization: We optimize maximum class separability in the binary space. We introduce a margin on distances between dissimilar image pairs as measured in the binary space. In addition to pair-wise distances, we draw inspiration from Fisher’s Linear Discriminant Analysis (Fisher LDA) to maximize the binary distances between classes and at the same time minimize the binary distance of images within the same class. Experiments on CIFAR-10, NUS-WIDE and ImageNet100 demonstrate compact codes comparing favorably to the current state of the art.



---

