# Towards accurate post-training network quantization via bit-split and stitching

## Summary

Summary: The paper presents a Bit-Split and Stitching framework for lower-bit post-training quantization, which is validated on various computer vision tasks and can achieve near-original model performance even when quantizing FP32 models to INT3 without fine-tuning. However, post-training quantization still suffers from the problem of significant accuracy degradation when both activations and weights are quantized into very low-bit integers.


## Target Task

computer vision

## Content

<Abstract: >In this paper, a Bit-Split and Stitching framework for lower-bit post-training quantization is proposed. The proposed framework is validated on various computer vision tasks, including image classification, object detection, and instance segmentation, with various network architectures. The framework can achieve near-original model performance even when quantizing FP32 models to INT3 without fine-tuning. Despite the advantages of post-training quantization, it has the problem of significant accuracy degradation, especially when both activations and weights are quantized into very low-bit integers.



---

