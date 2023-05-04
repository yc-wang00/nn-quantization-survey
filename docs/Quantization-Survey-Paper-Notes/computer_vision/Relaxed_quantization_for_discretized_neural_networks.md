# Relaxed quantization for discretized neural networks

## Summary

Summary: The paper introduces Relaxed Quantization (RQ), a differentiable quantization method that converts continuous distributions over network weights and activations into categorical distributions over the quantization grid and then relaxes them into continuous surrogates for efficient gradient-based optimization. The authors validate the performance of their method experimentally for classifying images using several datasets.


## Target Task

computer vision

## Content

<Abstract:>
Neural network quantization is a research field with significant impact on the deployment of models on resource-limited devices. The goal of this paper is to introduce Relaxed Quantization (RQ), a differentiable quantization method that transforms continuous distributions over network weights and activations into categorical distributions over the quantization grid, and subsequently relaxes them to continuous surrogates for efficient gradient-based optimization. Stochastic rounding can be seen as a special case of this approach, and the quantization grid can also be optimized using gradient descent. The authors validate the performance of their method experimentally for classifying images using the MNIST, CIFAR 10, and ImageNet datasets.



---

