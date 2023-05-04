# Fq-vit: Fully quantized vision transformer without retraining

## Summary

<Summary: >This paper presents a method called Power-of-Two Factor (PTF) to reduce inter-channel variation in LayerNorm inputs in order to improve the performance degradation of fully quantized vision transformers. They also propose a simplified method called Log-Int-Softmax (LIS) using 4-bit quantization and the BitShift operator. Their Fully Quantized Vision Transformer (FQ-ViT) outperforms previous works while using lower bit-width on attention maps and achieves no loss in accuracy degradation.


## Target Task

computer vision

## Content

<Abstract: >Network quantization has been widely used in real-world deployments to reduce model inference complexity. However, most existing quantization methods have been developed mainly on Convolutional Neural Networks (CNNs) and suffer when applied to fully quantized vision transformers. In this work, the authors present a systematic method called Power-of-Two Factor (PTF) to reduce the performance degradation and inference complexity of fully quantized vision transformers by reducing inter-channel variation in LayerNorm inputs. They also propose a method called Log-Int-Softmax (LIS) to simplify inference by using 4-bit quantization and the BitShift operator. They demonstrate that their Fully Quantized Vision Transformer (FQ-ViT) outperforms previous works while using lower bit-width on attention maps. They also achieve lossless accuracy degradation (1%) on fully quantized vision transformers.



---

