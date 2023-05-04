# Additive powers-of-two quantization: An efficient non-uniform discretization for neural networks

## Summary

<Summary: > The paper proposes Additive Powers-of-Two (APoT) quantization to efficiently and effectively quantize the bell-shaped and long-tailed weight and activation distribution in neural networks. The APoT quantization performs well due to high computational efficiency and good match with weight distribution, and uses simple reparameterization of the clipping function and weight normalization to refine weight distribution for more stable and consistent training. Experimental results show the proposed APoT quantization outperforms state-of-the-art methods and achieves competitive accuracy with full-precision models. For example, 4-bit quantized ResNet-50 on ImageNet achieves a 76.6% top-1 accuracy and reduces computational cost by 22% compared with uniformly quantized counterpart, without implementing bells and whistles.


## Target Task

computer vision

## Content

<Abstract: > We propose Additive Powers-of-Two (APoT) quantization, an efficient non-uniform quantization scheme for the bell-shaped and long-tailed distribution of weights and activations in neural networks. By constraining all quantization levels as the sum of Powers-of-Two terms, APoT quantization enjoys high computational efficiency and a good match with the distribution of weights. A simple reparameterization of the clipping function is applied to generate a better-defined gradient for learning the clipping threshold. Moreover, weight normalization is presented to refine the distribution of weights to make the training more stable and consistent. Experimental results show that our proposed method outperforms state-of-the-art methods, and is even competitive with the full-precision models, demonstrating the effectiveness of our proposed APoT quantization. For example, our 4-bit quantized ResNet-50 on ImageNet achieves 76.6% top-1 accuracy without bells and whistles; meanwhile, our model reduces 22% computational cost compared with the uniformly quantized counterpart.



---

