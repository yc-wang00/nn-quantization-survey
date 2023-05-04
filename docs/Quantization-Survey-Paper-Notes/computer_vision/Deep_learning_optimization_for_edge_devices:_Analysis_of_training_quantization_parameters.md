# Deep learning optimization for edge devices: Analysis of training quantization parameters

## Summary

Summary: This paper discusses the problem of convolution neural network quantization, which involves converting floating-point into integer-point numbers, and its importance in optimizing network inference while preserving its robustness. It also emphasizes the need for comparing different quantization configurations to understand the selection of hyperparameters during training. The paper performs an in-depth analysis of parameters in quantization aware training to evaluate their impact on the accuracy of the deep neural network aimed at performing efficient calculations on resource-constrained devices.


## Target Task

computer vision

## Content

<Abstract: >This paper focuses on convolution neural network quantization problem. The quantization has a distinct stage of data conversion from ﬂoating-point into integer-point numbers. In general, the process of quantization is associated with the reduction of the matrix dimension via limited precision of the numbers. However, the training and inference stages of deep learning neural network are limited by the space of the memory and a variety of factors including programming complexity and even reliability of the system. On the whole the process of quantization becomes more and more popular due to signiﬁcant impact on performance and minimal accuracy loss. Various techniques for networks quantization have been already proposed, including quantization aware training and integer arithmetic-only inference. Yet, a detailed comparison of various quantization conﬁgurations, combining all proposed methods haven’t been presented yet. This comparison is important to understand selection of quantization hyperparameters during training to optimize networks for inference while preserving their robustness. In this work, we perform in-depth analysis of parameters in the quantization aware training, the process of simulating precision loss in the forward pass by quantizing and dequantizing tensors. Speciﬁcally, we modify rounding modes, input preprocessing, output data signedness, bitwidth of the quantization and locations of precision loss simulation to evaluate how they affect accuracy of deep neural network aimed at performing efﬁcient calculations on resource-constrained devices. Keywords—Deep neural network, quantization, quantization aware training, data analysis, artiﬁcial intelligence, edge devices



---

