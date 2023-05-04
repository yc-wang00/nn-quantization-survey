# Deep neural network compression by in-parallel pruning-quantization

## Summary

<Summary: >This paper proposes a deep network compression algorithm called CLIP-Q(Compression Learning by In-Parallel Pruning-Quantization) which jointly performs weight pruning and quantization. The approach is capable of recovering from premature pruning errors, which is an advantage over two-stage approaches. CLIP-Q achieves state-of-the-art performance in network compression on various architectures including AlexNet, VGGNet, GoogLeNet and ResNet, according to experiments on ImageNet.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks enable state-of-the-art accuracy on visual recognition tasks such as image classification and object detection. However, modern networks contain millions of learned connections, and the current trend is towards deeper and more densely connected architectures. In this paper, we propose a deep network compression algorithm that performs weight pruning and quantization jointly, and in parallel with fine-tuning. Our approach takes advantage of the complementary nature of pruning and quantization and recovers from premature pruning errors, which is not possible with two-stage approaches. In experiments on ImageNet, CLIP-Q (Compression Learning by In-Parallel Pruning-Quantization) improves the state-of-the-art in network compression on AlexNet, VGGNet, GoogLeNet, and ResNet.



---

