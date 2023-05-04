# Quantization error as a metric for dynamic precision scaling in neural net training

## Summary

Summary: The paper introduces a dynamic precision scaling scheme that uses reduced numerical precision during training to reduce the computational cost of training. The proposed scheme achieves 98.8% test accuracy on the MNIST dataset using an average bit-width of just 16 bits for weights and 14 bits for activations, compared to the standard 32-bit values.


## Target Task

computer vision

## Content

<Abstract:> Recent work has explored reduced numerical precision for parameters, activations, and gradients during neural network training as a way to reduce the computational cost of training. We present a novel dynamic precision scaling (DPS) scheme. Using stochastic fixed-point rounding, a quantization-error based scaling scheme, and dynamic bit-widths during training, we achieve 98.8% test accuracy on the MNIST dataset using an average bit-width of just 16 bits for weights and 14 bits for activations, compared to the standard 32-bit floating point values used in deep learning frameworks.



---

