# Nonuniform-to-Uniform Quantization: Towards Accurate Quantization via Generalized Straight-Through Estimation

## Summary

<Summary: >This paper introduces a method called Nonuniform-to-Uniform Quantization (N2UQ) that aims to maintain the superior representation capacity of non-uniform quantization methods while remaining hardware-friendly and efficient for model inference. The method learns flexible in-equidistant input thresholds to better fit underlying distributions while quantizing real-valued inputs into equidistant output levels. G-STE is used to train quantized network with the learnable input thresholds. Additionally, entropy preserving regularization is considered to reduce information loss in weight quantization. N2UQ outperforms state-of-the-art non-uniform quantization methods by a margin of 0.5∼1.7% on ImageNet, even with uniformly quantized weights and activations. Code and models are available at https://github.com/liuzechun/Nonuniform-to-Uniform-Quantization.


## Target Task

computer vision

## Content

<Abstract: >The nonuniform quantization strategy for compressing
neural networks usually achieves better performance than
its counterpart, i.e., uniform strategy, due to its superior representational capacity. However, many nonuniform quantization methods overlook the complicated projection process in implementing the nonuniformly quantized weights/activations, which incurs non-negligible time and space overhead in hardware deployment. In this study, we propose Nonuniform-to-Uniform Quantization (N2UQ), a method that can maintain the strong representation ability of nonuniform methods while being hardware-friendly and efficient as the uniform quantization for model inference. We achieve this through learning the flexible in-equidistant input thresholds to better fit the underlying distribution while quantizing these real-valued inputs into equidistant output levels. To train the quantized network with learnable input thresholds, we introduce a generalized straight-through estimator (G-STE) for intractable backward derivative calculation w.r.t. threshold parameters. Additionally, we consider entropy preserving regularization to further reduce information loss in weight quantization. Even under this adverse constraint of imposing uniformly quantized weights and activations, our N2UQ outperforms state-of-the-art nonuniform quantization methods by 0.5∼1.7% on ImageNet, demonstrating the contribution of N2UQ design. Code and models are available at: https://github.com/liuzechun/Nonuniform-to-Uniform-Quantization.



---

