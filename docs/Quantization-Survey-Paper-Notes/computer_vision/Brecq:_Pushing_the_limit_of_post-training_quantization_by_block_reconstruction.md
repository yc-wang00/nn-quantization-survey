# Brecq: Pushing the limit of post-training quantization by block reconstruction

## Summary

<Summary: > The paper proposes a Post-training Quantization (PTQ) framework called BRECQ, which can quantize the neural network to INT2 for the first time, by reconstructing the building blocks one-by-one to balance cross-layer dependency and generalization error. The framework incorporates mixed precision technique by approximating inter-layer and intra-layer sensitivity. The experiments show that PTQ can achieve 4-bit ResNet and MobileNetV2 comparable to QAT, with 240x faster production of quantized models.


## Target Task

computer vision

## Content

<Abstract: >We propose a novel Post-training Quantization (PTQ) framework, called BRECQ, which is capable of pushing the bitwidth in PTQ down to INT2 for the first time. BRECQ reconstructs the building blocks in neural networks one-by-one to achieve a good balance between cross-layer dependency and generalization error. We incorporate mixed precision technique in our framework by approximating the inter-layer and intra-layer sensitivity. Our experiments show that PTQ can attain 4-bit ResNet and MobileNetV2 comparable with QAT and enjoy 240x faster production of quantized models.



---

