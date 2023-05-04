# Standard Deviation-Based Quantization for Deep Neural Networks

## Summary

<Summary: > The paper proposes a novel framework to quantize deep neural networks using the standard deviation of the network's weight and activation distributions. A logarithmic quantization scheme is also proposed to quantize weights to power-of-two discrete values. The method outperforms existing work on CIFAR10 and ImageNet datasets and achieves better accuracy performance with 3-bit weights and activations when compared to full-precision models. The proposed scheme simultaneously prunes the network's parameters and allows for flexible adjustment of the pruning ratio during the quantization process.


## Target Task

computer vision

## Content

<Abstract: >Quantization of deep neural networks is a promising approach to reduce the inference cost for resource-restricted devices. In this paper, the authors propose a new framework for quantizing intervals (discrete values) using the standard deviation of the network's weight and activation distributions. They also propose a novel base-2 logarithmic quantization scheme to quantize weights to power-of-two discrete values. According to their evaluations, their method outperforms existing work on CIFAR10 and ImageNet datasets and even achieves better accuracy performance with 3-bit weights and activations when compared to full-precision models. Their proposed scheme simultaneously prunes the network's parameters and allows for flexible adjustment of the pruning ratio during the quantization process.



---

