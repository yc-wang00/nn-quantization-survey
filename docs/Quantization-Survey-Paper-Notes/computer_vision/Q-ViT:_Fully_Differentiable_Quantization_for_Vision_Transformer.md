# Q-ViT: Fully Differentiable Quantization for Vision Transformer

## Summary

<Summary: > The proposed Q-ViT is a fully differentiable quantization technique for vision transformers that utilizes learnable parameters for quantization scales and bit-widths, with head-wise bit-width to decrease the size of Q-ViT while maintaining performance. The study also introduces a novel technique called switchable scale to address the convergence problem in the joint training of bit-widths and quantization scales. MSA and GELU are identified as important elements for ViT quantization, and experiments on different ViT models, such as DeiT and Swin Transformer, demonstrate the effectiveness of Q-ViT, which can achieve 3-bit quantization without significant loss in performance.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose a fully differentiable quantization method for vision transformer (ViT) named as Q-ViT. Our method uses learnable parameters for both quantization scales and bit-widths. We leverage head-wise bit-width to squeeze the size of Q-ViT while preserving performance. We also propose a novel technique named switchable scale to resolve the convergence problem in the joint training of quantization scales and bit-widths. Our study shows that the Multi-head Self-Attention (MSA) and the Gaussian Error Linear Units (GELU) are the key aspects for ViT quantization. We perform extensive experiments on different ViT models, such as DeiT and Swin Transformer, and demonstrate the effectiveness of our quantization method. Q-ViT pushes the limits of ViT quantization to 3-bit without heavy performance drop.



---

