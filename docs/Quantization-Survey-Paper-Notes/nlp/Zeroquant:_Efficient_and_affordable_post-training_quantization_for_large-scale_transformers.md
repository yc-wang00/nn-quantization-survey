# Zeroquant: Efficient and affordable post-training quantization for large-scale transformers

## Summary

<Summary: >Authors present a post-training quantization method called ZeroQuant for compressing large Transformer-based models. The approach involves an end-to-end quantization and inference pipeline with three components: hardware-friendly quantization scheme, affordable layer-by-layer knowledge distillation (LKD), and highly optimized quantization system backend support. ZeroQuant can reduce the precision for weights and activations to INT8 leading to 5.19x/4.16x speedup on BERT and GPT-3-style models compared to FP16 inference. ZeroQuant plus LKD can quantize weights in the fully-connected module to INT4 along with INT8 weights in the attention module and INT8 activations leading to a 3x memory footprint reduction compared to the FP16 model. ZeroQuant can be applied to GPT-J 6B and GPT-NeoX 20B language models, leading to similar accuracy as FP16 but achieving up to 5.2x better efficiency.


## Target Task

nlp

## Content

<Abstract: >In this work, the authors present an efficient and affordable post-training quantization approach called ZeroQuant to compress large Transformer-based models. ZeroQuant involves an end-to-end quantization and inference pipeline with three main components: a fine-grained hardware-friendly quantization scheme, a novel affordable layer-by-layer knowledge distillation algorithm (LKD), and a highly optimized quantization system backend support. The authors show that ZeroQuant can reduce the precision for weights and activations to INT8 in a cost-free way for both BERT and GPT-3-style models with minimal accuracy impact, which leads to up to 5.19x/4.16x speedup on those models compared to FP16 inference. ZeroQuant plus LKD can affordably quantize the weights in the fully-connected module to INT4 along with INT8 weights in the attention module and INT8 activations, resulting in a 3x memory footprint reduction compared to the FP16 model. The authors demonstrate that ZeroQuant can be directly applied to two of the largest open-sourced language models, including GPT-J 6B and GPT-NeoX 20B, for which the INT8 model achieves similar accuracy as the FP16 model but achieves up to 5.2x better efficiency.



---

