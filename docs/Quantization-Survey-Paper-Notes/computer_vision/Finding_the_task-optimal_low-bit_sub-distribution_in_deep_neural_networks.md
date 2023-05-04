# Finding the task-optimal low-bit sub-distribution in deep neural networks

## Summary

<Summary: >The paper discusses an adaptive-mapping quantization method that uses a concrete Gaussian Mixture to learn an optimal sub-distribution inherent within models. The method helps reduce the memory footprint and computation complexity while improving performance in tasks like image classification and object detection.


## Target Task

computer vision

## Content

<Abstract: >Quantized neural networks require smaller memory footprints and lower computation complexity, making them efficient for deployment. However, quantization leads to a distribution divergence from the original network, which can degrade performance. This paper presents an adaptive-mapping quantization method to learn an optimal latent sub-distribution inherent within models and smoothly approximated with a concrete Gaussian Mixture. The network weights are projected in compliance with the GM-approximated sub-distribution, which evolves along with the weight update in a co-tuning schema guided by the direct task-objective optimization. The proposed method is demonstrated effective in image classification and object detection over various modern architectures and shows transferability.



---

