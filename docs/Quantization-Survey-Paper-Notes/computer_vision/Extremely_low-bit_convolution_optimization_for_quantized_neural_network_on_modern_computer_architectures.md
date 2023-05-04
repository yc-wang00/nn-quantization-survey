# Extremely low-bit convolution optimization for quantized neural network on modern computer architectures

## Summary

Summary: The paper discusses the effectiveness of quantization in reducing the size of deep neural networks without significant loss in accuracy. The authors explore optimization methods for performing extremely low-bit convolutions on diverse architectures such as ARM CPU (2-8 bits) and NVIDIA GPU (4-8 bits). They propose instruction schemes, data padding and packing optimizations, winograd algorithm, data partition mechanism and quantization fusion to achieve higher performance. The results of their implementations perform better than other state-of-the-art frameworks and libraries. This is the first work that efficiently implements extremely low-bit convolutions on ARM CPU and NVIDIA GPU.


## Target Task

computer vision

## Content

<Abstract: >With the continuous demand for higher accuracy of deep neural networks, the model size has increased significantly. Quantization is one of the most widely used model compression methods, which can effectively reduce the model size without severe accuracy loss. Modern processors such as ARM CPU and NVIDIA GPU have already provided the support of low-bit arithmetic instructions. However, there lack efficient and practical optimizations for convolution computation towards extremely low-bit on ARM CPU (e.g., 2 ∼8-bit) and NVIDIA GPU (e.g., 4-bit and 8-bit). This paper explores the performance optimization methods of extremely low-bit convolution on diverse architectures. On ARM CPU, we propose two instruction schemes for 2∼3-bit and 4∼8-bit convolution with corresponding register allocation methods. In addition, we re-design the GEMM computation with data padding and packing optimizations. We also implement winograd algorithm for convolution with some specific bit width (e.g., 4∼6-bit) to achieve higher performance. On NVIDIA GPU, we propose a data partition mechanism and multi-level memory access optimizations, to better adapt the computation to GPU thread and memory hierarchy. We also propose quantization fusion to eliminate unnecessary data access. The experiment results demonstrate our implementations achieve better performance of extremely low-bit convolution compared to the state-of-the-art frameworks and libraries such as ncnn and cuDNN. To the best of our knowledge, this is the first work that provides efficient implementations of extremely low-bit convolutions covering 2 ∼8-bit on ARM CPU and 4-bit/8-bit on NVIDIA GPU.



---

