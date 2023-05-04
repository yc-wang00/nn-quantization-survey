# Quantization of generative adversarial networks for efficient inference: a methodological study

## Summary

<Summary: > The paper discusses the challenges of deploying Generative Adversarial Networks (GANs) on edge devices due to their resource-intensive nature during inference. It proposes Quantization, a neural network compression technique that replaces floating-point computations with low-bit integer ones, which can facilitate hardware-friendly inference. Through an experimental study, the authors have discovered practical recipes that successfully quantized three diverse GAN architectures without compromising the quality of the original full-precision models, and made them easy to deploy on edge devices.


## Target Task

computer vision

## Content

<Abstract: > Generative adversarial networks (GANs) are highly resource-intensive during inference, making deployment on edge devices challenging. Quantization, a neural network compression technique that replaces floating-point computations with low-bit integer ones, can facilitate hardware-friendly inference. However, the performance of quantization techniques in application to GANs remains unclear. To address this challenge, the authors of this paper conducted an experimental study on state-of-the-art quantization techniques on three diverse GAN architectures: StyleGAN, Self-Attention GAN, and CycleGAN. The authors discovered practical recipes that successfully quantized these models for inference with 4/8-bit weights and 8-bit activations while preserving the quality of the original full-precision models.



---

