# Improving Low-Precision Network Quantization via Bin Regularization

## Summary

<Summary: >This paper proposes a novel weight regularization algorithm for improving the accuracy of low-precision neural network quantization. The proposed method achieves consistent improvements over state-of-the-art quantization-aware training methods for different low-precision networks, and in particular it improves the top-1 accuracy of 2-bit MobileNetV2 and MobileNetV3-Small by 3.9% and 4.9%, respectively, on ImageNet.


## Target Task

computer vision

## Content

<Abstract: > Model quantization is an important mechanism for energy-efficient deployment of deep neural networks on resource-constrained devices by reducing the bit precision of weights and activations. However, it remains challenging to maintain high accuracy as bit precision decreases, especially for low-precision networks (e.g., 2-bit MobileNetV2). In this work, a novel weight regularization algorithm for improving low-precision network quantization is proposed. Experiments demonstrate that the proposed method achieves consistent improvements over the state-of-the-art quantization-aware training methods for different low-precision networks. Particularly, the proposed bin regularization improves LSQ for 2-bit MobileNetV2 and MobileNetV3-Small by 3.9% and 4.9% top-1 accuracy on ImageNet, respectively.



---

