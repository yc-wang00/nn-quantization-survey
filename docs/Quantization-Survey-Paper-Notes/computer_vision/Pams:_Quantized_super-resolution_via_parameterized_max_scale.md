# Pams: Quantized super-resolution via parameterized max scale

## Summary

Summary: The paper proposes a new quantization scheme called PArameterized Max Scale (PAMS) for super-resolution (SR) tasks that adaptively explores the upper bound of the quantization range and introduces a structured knowledge transfer (SKT) loss for fine-tuning of the quantized network. Experiments showed that PAMS scheme can compress and accelerate the existing SR models and achieve state-of-the-art results on the Set5 benchmark dataset.


## Target Task

computer vision

## Content

<Abstract: > Deep convolutional neural networks have become standard for super-resolution (SR) task. However, the huge memory cost and computation overhead limit their practical deployment especially on resource-limited devices. Previous quantization approaches have relied on fixed-point operations, which may lead to significant performance loss when both weights and activations are quantized. To address these issues, a new quantization scheme is proposed named PArameterized Max Scale (PAMS) that adaptively explores the upper bound of the quantization range by applying the trainable truncated parameter. A structured knowledge transfer (SKT) loss is also introduced for fine-tuning of the quantized network. Experiments showed that the proposed PAMS scheme can well compress and accelerate the existing SR models, and achieve a new state-of-the-art on the Set5 benchmark. Keywords: Super Resolution Network Quantization



---

