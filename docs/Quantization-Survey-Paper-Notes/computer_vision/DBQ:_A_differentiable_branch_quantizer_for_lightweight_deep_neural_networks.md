# DBQ: A differentiable branch quantizer for lightweight deep neural networks

## Summary

<Summary: >The paper proposes a new fully differentiable non-uniform quantizer (DBQ) which can efficiently map onto ternary-based dot product engines to reduce the computational and storage complexity of deep neural networks. This quantizer successfully quantizes lightweight networks such as MobileNetV1, MobileNetV2, and ShuffleNetV2 with minimal training overhead and achieves state-of-the-art results with the best accuracy-complexity trade-off on CIFAR-10, ImageNet, and Visual Wake Words datasets.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks have high computational and storage complexity, which limits their deployment on resource-constrained devices. To reduce the cost of implementing these networks, various complexity reduction techniques have been used including lightweight architecture design and parameter quantization. However, existing quantization techniques fail to replicate their success on lightweight architectures such as MobileNet. In this paper, a novel fully differentiable non-uniform quantizer (DBQ) is proposed that can be efficiently mapped onto ternary-based dot product engines. Comprehensive experiments on CIFAR-10, ImageNet, and Visual Wake Words datasets show that the proposed quantizer successfully quantizes lightweight networks such as MobileNetV1, MobileNetV2, and ShuffleNetV2 with minimal training overhead. DBQ achieves state-of-the-art results with the best accuracy-complexity trade-off.



---

