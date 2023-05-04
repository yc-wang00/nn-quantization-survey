# Differentiable soft quantization: Bridging full-precision and low-bit neural networks

## Summary

Summary: The authors propose a method called Differentiable Soft Quantization (DSQ) to train low-bit neural networks. DSQ approximates standard quantization, maintains accurate gradients in backward propagation and reduces quantization loss. They show through experiments that DSQ outperforms state-of-the-art quantization methods and present an efficient implementation for deploying 2 to 4-bit DSQ on devices with ARM architecture, achieving up to 1.7× speedup compared to the open-source 8-bit high-performance inference framework NCNN.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors propose a Differentiable Soft Quantization (DSQ) method to bridge the gap between full-precision and low-bit neural networks. DSQ can evolve during training to approximate standard quantization and can help pursue accurate gradients in backward propagation while reducing quantization loss. The authors demonstrate through extensive experiments over several popular network structures that training low-bit neural networks with DSQ outperforms state-of-the-art quantization methods. The authors also present an efficient implementation for deploying 2 to 4-bit DSQ on devices with ARM architecture, achieving up to 1.7× speedup compared to the open-source 8-bit high-performance inference framework NCNN [31].



---

