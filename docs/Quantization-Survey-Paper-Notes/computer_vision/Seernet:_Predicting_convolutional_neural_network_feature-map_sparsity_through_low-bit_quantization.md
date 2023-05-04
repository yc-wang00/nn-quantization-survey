# Seernet: Predicting convolutional neural network feature-map sparsity through low-bit quantization

## Summary

Summary: The paper proposed a method to accelerate CNN inference by utilizing the sparsity of feature maps. The method involves obtaining a binary sparsity mask of the output feature maps through a highly quantized version of the original network, followed by a full-precision sparse convolution. The approach is applicable to general CNN networks without needing to train additional auxiliary networks, and incurs negligible accuracy drop compared to the original network.


## Target Task

computer vision

## Content

<Abstract: > In this paper, we present a novel and general method to accelerate convolutional neural network (CNN) inference by taking advantage of feature map sparsity. We experimentally demonstrate that a highly quantized version of the original network is sufficient in predicting the output sparsity accurately, and verify that leveraging such sparsity in inference incurs negligible accuracy drop compared with the original network. To accelerate inference, for each convolution layer, our approach first obtains a binary sparsity mask of the output feature maps by running inference on a quantized version of the original network layer and then conducts a full-precision sparse convolution to find out the precise values of the non-zero outputs. Compared with existing work, our approach avoids the overhead of training additional auxiliary networks, while is still applicable to general CNN networks without being limited to certain application domains.



---

