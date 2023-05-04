# Learnable companding quantization for accurate low-bit neural networks

## Summary

<Summary: > The authors present a novel non-uniform quantization method called learnable companding quantization (LCQ) for 2-, 3-, and 4-bit models. LCQ optimizes model weights and learnable companding functions that can non-uniformly control the quantization levels of weights and activations. The experimental results demonstrate favorable performance in reducing memory consumption while maintaining accuracy for image classification and object detection tasks. The 2-bit ResNet-50 model on ImageNet achieved a top-1 accuracy of 75.1% with only a 1.7% gap compared to full-precision models.


## Target Task

computer vision

## Content

<Abstract: >Quantizing neural networks with extremely low-bit precision is a useful method for reducing memory consumption and improving inference speed, but it often results in reduced accuracy. In this paper, the authors propose a novel non-uniform quantization method called learnable companding quantization (LCQ) for 2-, 3-, and 4-bit models. LCQ optimizes model weights and learnable companding functions that can non-uniformly control the quantization levels of weights and activations. The authors also present a new weight normalization technique for stable training. Experimental results show that LCQ outperforms conventional methods and reduces the gap between quantized and full-precision models for image classification and object detection tasks. The 2-bit ResNet-50 model on ImageNet achieved a top-1 accuracy of 75.1% with only a 1.7% gap compared to full-precision models.



---

