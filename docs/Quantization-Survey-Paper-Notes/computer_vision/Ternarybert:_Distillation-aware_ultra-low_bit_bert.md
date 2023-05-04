# Ternarybert: Distillation-aware ultra-low bit bert

## Summary

Summary: The authors present TernaryBERT, a method that ternarizes the weights of pre-trained BERT models. They use approximation-based and loss-aware ternarization and investigate the ternarization granularity of different parts of BERT. The training process involves knowledge distillation to reduce accuracy degradation. TernaryBERT performs better than other BERT quantization methods while being 14.9x smaller. The authors also discuss other compression methods and their challenges in ultra-low bit quantization.


## Target Task

computer vision

## Content

<Abstract:> In this work, the authors propose TernaryBERT, a method to compress the pre-trained BERT model by ternarizing its weights. They use approximation-based and loss-aware ternarization methods and investigate the ternarization granularity of different parts of BERT. To reduce accuracy degradation, they leverage knowledge distillation in the training process. Experiments show that TernaryBERT outperforms other BERT quantization methods and achieves comparable performance as the full-precision model while being 14.9x smaller. The authors also discuss various other compression methods for neural networks, such as low-rank approximation, weight sharing, pruning, adaptive depth and/or width, and quantization, and their challenges in ultra-low bit quantization.



---

