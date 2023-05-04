# Clip-q: Deep network compression learning by in-parallel pruning-quantization

## Summary

Summary: The paper proposes a combined approach of network pruning and weight quantization that perform pruning and quantization jointly using a single learning framework. The proposed CLIP-Q method compresses the deep neural networks, including AlexNet, GoogLeNet, and ResNet-50 while preserving the accuracy on ImageNet.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks enable state-of-the-art accuracy on visual recognition tasks such as image classification and object detection. However, modern deep networks contain millions of learned weights; a more efficient utilization of computation resources would assist in a variety of deployment scenarios, from embedded platforms with resource constraints to computing clusters running ensembles of networks. In this paper, we combine network pruning and weight quantization in a single learning framework that performs pruning and quantization jointly, and in parallel with fine-tuning. This allows us to take advantage of the complementary nature of pruning and quantization and to recover from premature pruning errors, which is not possible with current two-stage approaches. Our proposed CLIP-Q method (Compression Learning by In-Parallel Pruning-Quantization) compresses AlexNet by 51-fold, GoogLeNet by 10-fold, and ResNet-50 by 15-fold, while preserving the uncompressed network accuracies on ImageNet.



---

