# Transform-based feature map compression for cnn inference

## Summary

<Summary: > The paper introduces a novel hardware-friendly transform-based approach, named 1D-Discrete Cosine Transform on Channel dimension with Masks (DCT-CM), to compress activations in deep convolutional neural networks (CNNs) by combining DCT, masks and coding formats. The proposed algorithm achieves a high compression ratio of 2.9x on ResNet-50 with an 8-bit quantization scheme, which can reduce data transfer bandwidth and power consumption.


## Target Task

computer vision

## Content

<Abstract: > To achieve higher accuracy in machine learning tasks, deep convolutional neural networks (CNNs) are designed, but their large memory access leads to high power consumption. Various hardware-friendly compression methods have been proposed to reduce data transfer bandwidth by exploiting the sparsity of feature maps, but most of them focus on designing specialized encoding formats to increase compression ratio. In this paper, a novel hardware-friendly transform-based method named 1D-Discrete Cosine Transform on Channel dimension with Masks (DCT-CM) is proposed, which intelligently combines DCT, masks, and a coding format to compress activations. The proposed algorithm achieves an average compression ratio of 2.9× during inference on ResNet-50 with an 8-bit quantization scheme.



---

