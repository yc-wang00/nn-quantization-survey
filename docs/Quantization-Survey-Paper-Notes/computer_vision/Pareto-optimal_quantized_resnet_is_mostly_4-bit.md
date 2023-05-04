# Pareto-optimal quantized resnet is mostly 4-bit

## Summary

Summary: This paper investigates the effects of quantization on ResNet models and their compute cost-quality tradeoff curves. The results suggest that 4-bit quantized models yield the best Pareto curve, which dominates the bfloat16 compute cost-quality tradeoff curve. The paper achieves state-of-the-art results on ImageNet for 4-bit ResNet-50 with quantization-aware training. The authors motivate further research into optimal numeric formats for quantization and the development of machine learning accelerators supporting these formats.


## Target Task

computer vision

## Content

<Abstract: Quantization has become a popular technique to compress neural networks and reduce compute cost, but most prior work focuses on studying quantization without changing the network size. In this work, we use ResNet as a case study to systematically investigate the effects of quantization on inference compute cost-quality tradeoff curves. Our results suggest that for each bﬂoat16 ResNet model, there are quantized models with lower cost and higher accuracy; in other words, the bﬂoat16 compute cost-quality tradeoff curve is Pareto-dominated by the 4-bit and 8-bit curves, with models primarily quantized to 4-bit yielding the best Pareto curve. Furthermore, we achieve state-of-the-art results on ImageNet for 4-bit ResNet-50 with quantization-aware training, obtaining a top-1 eval accuracy of 77.09%. Our work motivates further research into optimal numeric formats for quantization, as well as the development of machine learning accelerators supporting these formats.>



---

