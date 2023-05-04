# Automatic pruning for quantized neural networks

## Summary

Summary: The paper proposes a combination of neural network quantization and pruning to further compress the network. The technique involved an effective pruning strategy for selecting redundant low-precision filters and the use of Bayesian optimization to determine the pruning ratio. The proposed technique achieved successful results on CIFAR-10 and ImageNet datasets with various architectures and precisions.


## Target Task

computer vision

## Content

<Abstract: >
Neural network quantization and pruning are two techniques commonly used to reduce the computational complexity and memory footprint of these models for deployment. However, most existing pruning strategies operate on full-precision and cannot be directly applied to discrete parameter distributions after quantization. In contrast, we study a combination of these two techniques to achieve further network compression. In particular, we propose an effective pruning strategy for selecting redundant low-precision ﬁlters. Furthermore, we leverage Bayesian optimization to efﬁciently determine the pruning ratio for each layer. We conduct extensive experiments on CIFAR-10 and ImageNet with various architectures and precisions. In particular, for ResNet-18 on ImageNet, we prune 26.12% of the model size with Binarized Neural Network quantization, achieving a top-1 classiﬁcation accuracy of 47.32% in a model of 2.47 MB and 59.30% with a 2-bit DoReFa-Net in 4.36 MB.



---

