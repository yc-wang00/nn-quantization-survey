# Q-ViT: Accurate and Fully Quantized Low-bit Vision Transformer

## Summary

Summary: The paper proposes a method to address the performance drop in low-bit vision transformers caused by information distortion during quantization. The authors developed an information rectification module and a distribution guided distillation scheme, resulting in a fully quantized ViT achieving better performance than prior arts. The Q-ViT can theoretically accelerate the ViT-S by 6.14x and achieves about 80.9% Top-1 accuracy, even surpassing the full-precision counterparts.


## Target Task

computer vision

## Content

<Abstract: > The large pre-trained vision transformers have proven effective in various computer vision tasks, but are limited in their deployment on resource-constrained devices due to expensive computational and memory costs. Quantization is a method that reduces computation and memory consumption by using low-bit parameters and bit-wise operations. However, low-bit ViTs usually suffer from a significant performance drop compared to their real-valued counterparts. In this work, the authors identify the bottleneck for severe performance drop comes from the information distortion of the low-bit quantized self-attention map. They then develop an information rectification module and a distribution guided distillation scheme for fully quantized vision transformers to effectively eliminate such distortion, leading to a fully quantized ViTs. Experimental results show that their method achieves better performance than prior arts, where the Q-ViT can theoretically accelerates the ViT-S by 6.14x and achieves about 80.9% Top-1 accuracy, even surpassing the full-precision counterparts.



---

