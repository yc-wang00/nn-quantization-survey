# Subtensor quantization for mobilenets

## Summary

<Summary: > This paper presents a study on the challenges faced while quantizing Mobilenet architecture and proposes an alternative approach that uses asymmetric quantization to support depthwise convolutions, achieving near-floating point accuracy in 8-bit post-training quantized inference on the ImageNet dataset, without the need for per-channel or training-aware methods.


## Target Task

computer vision

## Content

<Abstract: > Quantization is an essential technique for optimizing deep neural network (DNN) inference, particularly for embedded systems with strict constraints on memory and power consumption. However, not all DNN designs are easily quantifiable, such as the widely-used Mobilenet architecture. In this paper, the authors present a case study on the challenges of quantizing the Mobilenet architecture and propose an alternative approach that enhances asymmetric quantization to support depthwise convolutions. They demonstrate that their approach achieves near-floating point accuracy in 8-bit post-training quantized inference on the ImageNet dataset, without the need for per-channel or training-aware methods.



---

