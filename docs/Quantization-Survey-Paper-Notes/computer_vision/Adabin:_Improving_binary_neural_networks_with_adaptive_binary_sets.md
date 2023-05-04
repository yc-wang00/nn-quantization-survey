# Adabin: Improving binary neural networks with adaptive binary sets

## Summary

<Summary: > The paper proposes a novel technique named AdaBin that uses binary quantization function based on the center position and distance of 1-bit values and gradient-based optimization method to find the optimal binary sets of activation for each layer, rather than using a fixed set. Using this technique, the paper achieves state-of-the-art performance in Binary Neural Networks, obtaining a 66.4% Top-1 accuracy on ImageNet using ResNet-18 architecture and a 69.4 mAP on PASCAL VOC using SSD300.


## Target Task

computer vision

## Content

<Abstract: >This paper studies Binary Neural Networks (BNNs) that binarize weights and activations into 1-bit values, reducing memory usage and computational complexity. However, conventional sign functions cannot effectively binarize complex architectures with diverse weight and activation distributions. To solve this, this paper presents AdaBin, a simple approach to adaptively obtain optimal binary sets for each layer, rather than a fixed set. The method uses a new binary quantization function based on the center position and distance of 1-bit values, and introduces an equalization method for aligning the symmetrical center of binary distribution to real-valued distribution, and a gradient-based optimization method to find the optimal binary sets of activations. AdaBin achieves state-of-the-art performance, obtaining a 66.4% Top-1 accuracy on the ImageNet using ResNet-18 architecture and a 69.4 mAP on PASCAL VOC using SSD300.



---

