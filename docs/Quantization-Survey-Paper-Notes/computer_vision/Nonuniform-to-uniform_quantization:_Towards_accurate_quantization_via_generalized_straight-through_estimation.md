# Nonuniform-to-uniform quantization: Towards accurate quantization via generalized straight-through estimation

## Summary

<Summary: >The paper proposes Nonuniform-to-Uniform Quantization (N2UQ), a method that can maintain the representation ability of nonuniform quantization while being hardware-friendly for model inference by learning flexible in-equidistant input thresholds to quantize inputs efficiently into equidistant output levels. The proposed approach outperforms state-of-the-art nonuniform quantization methods in ImageNet by 0.5∼1.7%.


## Target Task

computer vision

## Content

<Abstract: >The nonuniform quantization strategy for compressing neural networks usually achieves better performance than its counterpart, i.e., uniform strategy, due to its superior representational capacity. However, many nonuniform quantization methods overlook the complicated projection process in implementing the nonuniformly quantized weights/activations, which incurs non-negligible time and space overhead in hardware deployment. In this study, we propose Nonuniform-to-Uniform Quantization (N2UQ), a method that can maintain the strong representation ability of nonuniform methods while being hardware-friendly and efficient as the uniform quantization for model inference. We achieve this through learning the flexible in-equidistant input thresholds to better fit the underlying distribution while quantizing these real-valued inputs into equidistant output levels. To train the quantized network with learnable input thresholds, we introduce a generalized straight-through estimator (G-STE) for intractable backward derivative calculation w.r.t. threshold parameters. Additionally, we consider entropy preserving regularization to further reduce information loss in weight quantization. Even under this adverse constraint of imposing uniformly quantized weights and activations, our N2UQ outperforms state-of-the-art nonuniform quantization methods by 0.5∼1.7% on ImageNet, demonstrating the contribution of N2UQ design. Code and models are available at: https://github.com/liuzechun/Nonuniform-to-Uniform-Quantization.>



---

