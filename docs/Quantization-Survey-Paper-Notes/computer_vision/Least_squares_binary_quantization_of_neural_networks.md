# Least squares binary quantization of neural networks

## Summary

<Summary: >This paper introduces a unified framework to analyze different scaling strategies for binary quantization of weights and activations of deep neural networks. Their novel 2-bits quantization has the least square error with proofs for optimality and empirical error analysis. Their quantization algorithms can be implemented efficiently on the hardware using bitwise operations. They conducted experiments on the ImageNet dataset and showed a reduced accuracy gap when using the proposed least squares quantization algorithms.


## Target Task

computer vision

## Content

<Abstract: >Quantizing weights and activations of deep neural networks results in significant improvement in inference efficiency at the cost of lower accuracy. A source of the accuracy gap between full precision and quantized models is the quantization error. In this work, we focus on the binary quantization, in which values are mapped to -1 and 1. We provide a unified framework to analyze different scaling strategies. Inspired by the pareto-optimality of 2-bits versus 1-bit quantization, we introduce a novel 2-bits quantization with provably least squares error. Our quantization algorithms can be implemented efficiently on the hardware using bitwise operations. We present proofs to show that our proposed methods are optimal, and also provide empirical error analysis. We conduct experiments on the ImageNet dataset and show a reduced accuracy gap when using the proposed least squares quantization algorithms.



---

