# [PDF][PDF] Variational network quantization

## Summary

<Summary: >The paper introduces a method for preparing neural networks for pruning and few-bit quantization by formulating it as a variational inference problem. A quantizing prior that leads to a multi-modal, sparse posterior distribution over weights is introduced, and a differentiable Kullback-Leibler divergence approximation for this prior is derived. Results are shown for ternary quantization on LeNet-5 (MNIST) and DenseNet (CIFAR-10), and the method does not require fine-tuning after quantization.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the preparation of a neural network for pruning and few-bit quantization is formulated as a variational inference problem. To this end, a quantizing prior that leads to a multi-modal, sparse posterior distribution over weights, is introduced and a differentiable Kullback-Leibler divergence approximation for this prior is derived. After training with Variational Network Quantization, weights can be replaced by deterministic quantization values with small to negligible loss of task accuracy (including pruning by setting weights to 0). The method does not require ﬁne-tuning after quantization. Results are shown for ternary quantization on LeNet-5 (MNIST) and DenseNet (CIFAR-10).



---

