# [PDF][PDF] KCNN: Kernel-wise Quantization to Remarkably Decrease Multiplications in Convolutional Neural Network.

## Summary

Summary: The paper proposes a new method called KCNN for quantizing floating-point weights separately in each kernel to reduce computational complexity in convolutional neural networks (CNNs). They use an aggressive Lloyd algorithm to obtain a closed-form solution and dual normalization to address the pathological curvature problem during fine-tuning. KCNN shows insignificant performance loss compared to floating-point counterparts.


## Target Task

computer vision

## Content

<Abstract: > Convolutional neural networks (CNNs) are state-of-the-art in computer vision tasks. However, their high computational power demand has limited their widespread adoption. Several methods have quantized the weights and activations to decrease computational complexity, but fixed-point or binary values may cause degradation in performance due to numerical information loss. In this paper, the authors propose KCNN, a method that quantizes floating-point weights in each kernel separately to multiple bit planes to decrease multiplications. The authors obtain a closed-form solution via an aggressive Lloyd algorithm and fine-tuning, and propose dual normalization to solve the pathological curvature problem during fine-tuning. The method shows negligible performance loss compared to floating-point counterparts.



---

