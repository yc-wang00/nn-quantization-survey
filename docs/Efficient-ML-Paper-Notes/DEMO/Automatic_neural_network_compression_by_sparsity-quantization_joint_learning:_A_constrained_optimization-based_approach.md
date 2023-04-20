# Automatic neural network compression by sparsity-quantization joint learning: A constrained optimization-based approach

## Summary

<Summary: >The paper proposes a framework for automatically pruning and quantizing Deep Neural Networks without requiring a manual setting for compression ratio. The framework shows promising results and can compress complex networks such as ResNet-50 and AlexNet without accuracy loss. The authors discuss the importance of compressing DNNs for deployment on low-resource devices and compare their framework with other automated model compression methods that rely on hyper-parameters and black-box optimization.


## Target Task

Target: Computer Vision

## Content

<Abstract: >In this research paper, the authors propose a framework to automatically prune and quantize Deep Neural Networks (DNNs) without manually setting the compression ratio for each layer. They show through experiments that their framework can compress ResNet-50 to be 836 times smaller and AlexNet to be 205 times smaller without accuracy loss on CIFAR-10 and ImageNet classification, respectively. The authors discuss the increased demand for deploying DNNs on devices with limited resources and highlight the importance of compressing DNNs while maintaining the accuracy under given resource constraints. They also review various compression techniques such as pruning and quantization and explain how they can be applied to reduce the resource requirement. Lastly, the paper compares the proposed framework with other automated model compression methods, which primarily rely on hyper-parameters and black-box optimization. </Abstract:>



---

