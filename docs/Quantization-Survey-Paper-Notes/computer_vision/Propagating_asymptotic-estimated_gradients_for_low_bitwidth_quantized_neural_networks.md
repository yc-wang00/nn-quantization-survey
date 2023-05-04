# Propagating asymptotic-estimated gradients for low bitwidth quantized neural networks

## Summary

Summary: The paper proposes a new method called Asymptotic-Quantized Estimator (AQE) to train non-differentiable quantized neural networks (QNNs) smoothly while maintaining the smoothness condition of the graph. The output function gradually approaches the quantized value during the training process, and at the end of training, the weights and activations are quantized to low-precision. The proposed MINW-Net achieves comparable results to other state-of-the-art QNNs on ImageNet dataset. AQE outperforms Straight-Through Estimator (STE) and is well-defined.


## Target Task

computer vision

## Content

<Abstract: >
The paper proposes a novel Asymptotic-Quantized Estimator (AQE) to estimate the gradient during the back-propagation process of the non-differentiable quantized neural networks (QNNs) training. The smoothness condition of the graph is maintained during the training process, and the output function gradually approaches the quantized value. At the end of training, the weights and activations have been quantized to low-precision, making the graph flow "non-smooth" non-linearities, which can be used to introduce the M-bit Inputs and N-bit Weights Network (MINW-Net) with low-precision weights and activations. AQE is well-defined and performs better than Straight-Through Estimator (STE). The proposed MINW-Net achieves comparable results with other state-of-the-art QNNs on ImageNet dataset.



---

