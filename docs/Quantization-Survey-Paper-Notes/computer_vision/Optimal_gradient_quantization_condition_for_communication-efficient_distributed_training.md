# Optimal gradient quantization condition for communication-efficient distributed training

## Summary

<Summary: > The paper discusses the issue of costly communication in deep neural network training with multiple devices in computer vision applications. Gradient quantization is proposed as a solution to reduce communication costs, however, it can lead to quantization error and a resulting model performance degradation. The paper introduces two novel quantization schemes, biased BinGrad and unbiased ORQ, for binary and multi-level gradient quantization respectively, which determine the optimal quantization levels through the deduced optimal condition. CIFAR and ImageNet datasets with popular convolutional neural networks were used in the experiments, and the proposed methods were found to be superior.


## Target Task

computer vision

## Content

<Abstract: > The communication of gradients is costly for training deep neural networks with multiple devices in computer vision applications. Gradient quantization is one of the common methods to reduce communication costs, but it can lead to quantization error in the training and result in model performance degradation. In this work, we deduce the optimal condition of both the binary and multi-level gradient quantization for any gradient distribution. Based on the optimal condition, we develop two novel quantization schemes: biased BinGrad and unbiased ORQ for binary and multi-level gradient quantization respectively, which dynamically determine the optimal quantization levels. Extensive experimental results on CIFAR and ImageNet datasets with several popular convolutional neural networks show the superiority of our proposed methods.



---

