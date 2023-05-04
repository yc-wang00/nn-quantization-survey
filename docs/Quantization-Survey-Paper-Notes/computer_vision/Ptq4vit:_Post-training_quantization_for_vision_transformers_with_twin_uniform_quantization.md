# Ptq4vit: Post-training quantization for vision transformers with twin uniform quantization

## Summary

Summary: This paper proposes a new method for quantizing neural networks called twin uniform quantization method and a Hessian-guided scaling factor evaluation. This method addresses the significant accuracy drops found in previous post-training quantization methods for vision transformers, leading to near-lossless prediction accuracy at 8-bit quantization. The authors develop a fast quantization framework called PTQ4ViT and present experimental results on the ImageNet classification task.


## Target Task

computer vision

## Content

<Abstract: >Quantization is a powerful method to compress neural networks, but previous post-training quantization methods have resulted in significant accuracy drops for vision transformers even at 8-bit quantization. In this paper, the authors propose the twin uniform quantization method and a Hessian-guided scaling factor evaluation to reduce quantization error on activation values. They also develop a fast quantization framework, PTQ4ViT. Experimental results show near-lossless prediction accuracy (less than 0.5% drop at 8-bit quantization) for quantized vision transformers on the ImageNet classification task.



---

