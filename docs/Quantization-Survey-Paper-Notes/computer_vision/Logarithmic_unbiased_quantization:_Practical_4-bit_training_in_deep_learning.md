# Logarithmic unbiased quantization: Practical 4-bit training in deep learning

## Summary

Summary: This paper proposes a logarithmic unbiased quantization method that can quantize both the forward and backward phases of DNN training to achieve 4-bit precision without any overhead. The proposed method achieves state-of-the-art results in 4-bit training without the need for specific hardware support for non-standard quantization. The authors further improve the performance to only 0.32% degradation after three epochs of high-precision fine-tuning, combined with a variance reduction method.


## Target Task

computer vision

## Content

<Abstract:> Quantization of weights and activations is a popular method to reduce the computational resources needed for training Deep Neural Networks (DNNs). However, 4-bit quantization only covers the forward phase of DNN training whereas quantization of the neural gradients, i.e., the loss gradients with respect to the outputs of intermediate neural layers, is also necessary to reduce the entire computational footprint. This paper suggests a logarithmic unbiased quantization (LUQ) method to quantize both the forward and backward phases of DNN training to achieve 4-bit precision without overhead. The proposed method achieves state-of-the-art results in 4-bit training without the need for specific hardware support for non-standard quantization. The authors further improve the performance to only 0.32% degradation after three epochs of high-precision fine-tuning, combined with a variance reduction method.



---

