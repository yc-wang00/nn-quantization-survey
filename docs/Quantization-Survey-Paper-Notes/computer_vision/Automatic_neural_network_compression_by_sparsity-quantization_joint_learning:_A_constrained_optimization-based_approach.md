# Automatic neural network compression by sparsity-quantization joint learning: A constrained optimization-based approach

## Summary

<Summary: > The paper proposes a framework for automatic pruning and quantization of DNNs while targeting a specific model size and maintaining model accuracy. The proposed method can compress the weights data of ResNet-50 to 836× smaller without a loss in accuracy on CIFAR-10 and compress AlexNet to be 205× smaller without accuracy loss on ImageNet classification. The authors discuss the need for compressing DNNs in resource-constrained devices and introduce pruning and quantization techniques as widely used methods for DNN compression. They propose their constrained optimization-based approach as an alternative to existing solutions that rely on human heuristic or black-box hyper-parameter optimization methods.


## Target Task

computer vision

## Content

<Abstract: > In this paper, the authors propose a framework to jointly prune and quantize Deep Neural Networks (DNNs) automatically without using human heuristic or black-box hyper-parameter optimization. The framework aims to compress the DNN models according to a target model size while maintaining their accuracy. The experiments show that their approach can compress the weights data of ResNet-50 to be 836× smaller without losing accuracy on CIFAR-10 and compress AlexNet to be 205× smaller without accuracy loss on ImageNet classification. The authors discuss the increased demand for deploying DNNs on resource-constrained devices and the critical need for compressing DNNs while maximizing their accuracy. They highlight pruning and quantization techniques as the most widely used methods for DNN compression and introduce the problem of finding the optimal compression ratio (i.e., sparsity or quantization bitwidth) for each layer in a way that meets the given resource budget. They also discuss existing solutions that tune the compression ratio based on human heuristic or black-box hyper-parameter optimization methods and propose their constrained optimization-based approach as an alternative.



---

