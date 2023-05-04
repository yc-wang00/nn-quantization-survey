# Efficient execution of quantized deep learning models: A compiler approach

## Summary

<Summary: > This paper proposes a compiler approach to execute pre-quantized models from deep learning frameworks effectively on different hardware platforms by introducing a Quantized Neural Network dialect to the compiler representation. By using QNN with the compilation of pre-quantized models, the proposed compiler approach achieves significant speedups on various hardware platforms, making it possible to achieve model execution performance comparable to state-of-the-art framework-specific solutions but on a broader range of hardware platforms.


## Target Task

computer vision

## Content

Abstract: A compiler approach is proposed in this paper to tackle the challenges of executing pre-quantized models from deep learning frameworks on a variety of hardware platforms. We introduce a Quantized Neural Network (QNN) dialect to the compiler representation to optimize pre-quantized INT8 models. The QNN-augmented deep learning compiler achieves speedups of up to 2.35x, 2.15x, 1.35x, and 1.40x on various hardware platforms including Intel Xeon Cascade Lake CPUs, Nvidia Tesla T4 GPUs, ARM Cortex-A CPUs on Raspberry Pi3 and Pi4, respectively. Using QNN with the compilation of pre-quantized models enables developers to achieve model execution performance comparable to state-of-the-art framework-specific solutions but on a wider range of hardware platforms.



---

