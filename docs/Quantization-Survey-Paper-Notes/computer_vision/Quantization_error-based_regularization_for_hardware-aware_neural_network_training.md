# Quantization error-based regularization for hardware-aware neural network training

## Summary

<Summary: >
The paper proposes a regularization strategy called QER, which aims to improve the accuracy of quantized neural networks. The regularization term based on quantization errors of weights is added to the loss function to reduce the quantization errors along with the original loss, thereby improving the accuracy. The proposed approach is evaluated on MNIST using a simple neural network model, and the results show that it achieves higher accuracy than the standard training approach with quantized forward propagation.


## Target Task

computer vision

## Content

Abstract: We propose “QER”, a novel regularization strategy for hardware-aware neural network training. Although quantized neural networks reduce computation power and resource consumption, it also degrades the accuracy due to quantization errors of the numerical representation, which are defined as differences between original numbers and quantized numbers. The QER solves such the problem by appending an additional regularization term based on quantization errors of weights to the loss function. The regularization term forces the quantization errors of weights to be reduced as well as the original loss. We evaluate our method by using MNIST on a simple neural network model. The evaluation results show that the proposed approach achieves higher accuracy than the standard training approach with quantized forward propagation.



---

