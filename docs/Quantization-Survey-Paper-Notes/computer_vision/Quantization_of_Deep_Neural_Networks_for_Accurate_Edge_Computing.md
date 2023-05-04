# Quantization of Deep Neural Networks for Accurate Edge Computing

## Summary

<Summary: >This paper discusses how weight quantization and pruning is applied to Deep Neural Networks to ready them for use in edge devices. While it is believed that quantization leads to performance degradation, the paper argues that regularization on weight representations can actually improve accuracy, and their experiments on three widely used applications show that quantization can improve accuracy by 1-4% with a significant memory reduction.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks (DNNs) have demonstrated their great potential in recent years, exceeding the performance of human experts in a wide range of applications. Due to their large sizes, however, compression techniques such as weight quantization and pruning are usually applied before they can be accommodated on the edge. It is generally believed that quantization leads to performance degradation, and plenty of existing works have explored quantization strategies aiming at minimum accuracy loss. In this paper, we argue that quantization, which essentially imposes regularization on weight representations, can sometimes help to improve accuracy. We conduct comprehensive experiments on three widely used applications: fully connected network (FCN) for biomedical image segmentation, convolutional neural network (CNN) for image classification on ImageNet, and recurrent neural network (RNN) for automatic speech recognition, and experimental results show that quantization can improve the accuracy by 1%, 1.95%, 4.23% on the three applications respectively with 3.5x-6.4x memory reduction.



---

