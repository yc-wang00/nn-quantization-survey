# Differentiable dynamic quantization with mixed precision and adaptive resolution

## Summary

Summary: The paper introduces a Differentiable Dynamic Quantization (DDQ) approach in neural network quantization. It is a hardware-friendly and fully differentiable approach which learns all of the tedious hyper-parameters like precision, dynamic range and stepsize. DDQ is capable of quantizing lightweight architectures like MobileNets and reduces training runtime by 25%. Extensive experiments show that DDQ outperforms prior arts on many networks and benchmarks, especially on efficient and compact models where it achieves lossless 4-bit quantization for MobileNetV2 on ImageNet.


## Target Task

computer vision

## Content

<Abstract: > Model quantization is challenging due to many tedious hyper-parameters such as precision (bitwidth), dynamic range (minimum and maximum discrete values) and stepsize (interval between discrete values). Unlike prior arts that carefully tune these values, we present a fully differentiable approach to learn all of them, named Differentiable Dynamic Quantization (DDQ), which has several benefits. DDQ is able to quantize challenging lightweight architectures like MobileNets, where different layers prefer different quantization parameters. DDQ is hardware-friendly and can be easily implemented using low-precision matrix-vector multiplication, making it capable in many hardware such as ARM. DDQ reduces training runtime by 25% compared to state-of-the-arts. Extensive experiments show that DDQ outperforms prior arts on many networks and benchmarks, especially when models are already efficient and compact. e.g. DDQ is the first approach that achieves lossless 4-bit quantization for MobileNetV2 on ImageNet.



---

