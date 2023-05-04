# Balanced quantization: An effective and efficient approach to quantized neural networks

## Summary

<Summary: >The paper discusses the limitations of uniform quantization in Quantized Neural Networks (QNNs), and proposes a new method to ensure the uniform distribution of values. The proposed method addresses the issue of imbalanced distribution of parameters in Neural Networks, which leads to underutilization of available bitwidth.


## Target Task

computer vision

## Content

<Abstract: >Quantized Neural Networks (QNNs), which use low bitwidth numbers for representing parameters and performing computations, have been proposed to reduce the computation complexity, storage size and memory usage. In QNNs, parameters and activations are uniformly quantized, such that the multiplications and additions can be accelerated by bitwise operations. However, distributions of parameters in Neural Networks are often imbalanced, such that the uniform quantization determined from extremal values may underutilize available bitwidth. In this paper, we propose a novel quantization method that can ensure the balance of distributions of quantized values.



---

