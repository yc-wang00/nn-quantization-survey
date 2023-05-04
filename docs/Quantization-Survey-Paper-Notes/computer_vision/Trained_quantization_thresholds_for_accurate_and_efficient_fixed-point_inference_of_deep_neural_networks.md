# Trained quantization thresholds for accurate and efficient fixed-point inference of deep neural networks

## Summary

<Summary: > In this paper, a method is proposed for training quantization thresholds using backpropagation and gradient descent for uniform symmetric quantizers. The quantizers are constrained to per-tensor scaling of weights and activations to make it feasible for hardware implementations. The empirical validation shows that the proposed approach achieves near-floating-point accuracy with less than 5 epochs on various CNNs for ImageNet classification, including traditionally difficult networks like MobileNets.


## Target Task

computer vision

## Content

<Abstract: > We propose a method for training quantization thresholds using standard backpropagation and gradient descent for uniform symmetric quantizers. Our approach shows a range-precision trade-off leading to better optima. The quantizers are constrained to per-tensor scaling of weights and activations to make it amenable for hardware implementations. We empirically validate them on various CNNs for ImageNet classification, and achieve near-floating-point accuracy on traditionally difficult networks such as MobileNets with less than 5 epochs.



---

