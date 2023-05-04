# Sharpness-aware Quantization for Deep Neural Networks

## Summary

Summary: The authors propose a new method called Sharpness-Aware Quantization (SAQ) that combines Sharpness-Aware Minimization (SAM) and quantization for model compression. SAQ shows state-of-the-art results in uniform quantization for convolutional neural networks and Transformers on various datasets, outperforming previous methods, including AdamW.


## Target Task

computer vision

## Content

<Abstract: >
In this paper, the authors propose a novel method called Sharpness-Aware Quantization (SAQ) to explore the effect of Sharpness-Aware Minimization (SAM) in model compression, particularly quantization for the first time. SAQ formulates a unified view of quantization and SAM by treating them as introducing quantization noises and adversarial perturbations to the model weights, respectively. Using an efficient training strategy, SAQ incurs little additional training overhead compared with the default optimizer. Extensive experiments on both convolutional neural networks and Transformers across various datasets show that SAQ improves the generalization performance of the quantized models, yielding state-of-the-art results in uniform quantization. The authors show that on ImageNet, SAQ outperforms AdamW by 1.2% on the Top-1 accuracy for a 4-bit ViT-B/16, and their 4-bit ResNet-50 surpasses the previous state-of-the-art method by 0.9% on the Top-1 accuracy.



---

