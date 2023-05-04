# BSQ: Exploring bit-level sparsity for mixed-precision neural network quantization

## Summary

<Summary: >The paper proposes a method called bit-level sparsity quantization (BSQ) for mixed-precision quantization of deep neural networks. This method induces bit-level sparsity to enable dynamic precision reduction, leading to a mixed-precision quantization scheme of the original model. With only one hyperparameter, the full mixed-precision space can be explored with a single gradient-based optimization process. Comparing to previous methods, BSQ achieves higher accuracy as well as higher bit reduction on various model architectures on the CIFAR-10 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract: >Mixed-precision quantization can potentially achieve the optimal tradeoff between performance and compression rate of deep neural networks. However, determining the exact quantization scheme lacks a systematic method. This work proposes bit-level sparsity quantization (BSQ) to tackle the mixed-precision quantization by inducing bit-level sparsity. BSQ can induce all-zero bits across a group of weight elements and realize the dynamic precision reduction, leading to a mixed-precision quantization scheme of the original model. The method enables the exploration of the full mixed-precision space with a single gradient-based optimization process, with only one hyperparameter to tradeoff the performance and compression. BSQ achieves both higher accuracy and higher bit reduction on various model architectures on the CIFAR-10 and ImageNet datasets comparing to previous methods.



---

