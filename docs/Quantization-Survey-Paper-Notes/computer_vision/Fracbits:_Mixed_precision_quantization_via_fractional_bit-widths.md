# Fracbits: Mixed precision quantization via fractional bit-widths

## Summary

Summary: The paper introduces FracBits, a learning-based algorithm for mixed precision quantization of deep neural networks. The algorithm optimizes the bit-width of each layer/kernel in the model to be a fractional status of two consecutive bit-widths, with a differentiable regularization term to meet resource constraints during quantization-aware training. Results show that FracBits achieves comparable or better performance than previous quantization methods with mixed precision on MobilenetV1/V2, ResNet18 under different resource constraints on the ImageNet dataset.


## Target Task

computer vision

## Content

<Abstract:>
Model quantization is a popular technique used to reduce the size and latency of deep neural networks. Mixed precision quantization is a more flexible approach that can achieve a better balance between computation cost and model accuracy. We propose a novel learning-based algorithm called FracBits, which derives mixed precision models end-to-end under target computation constraints and model sizes. FracBits optimizes the bit-width of each layer/kernel in the model to be a fractional status of two consecutive bit-widths, with a differentiable regularization term to meet resource constraints during quantization-aware training. Our final models demonstrate comparable or better performance than previous quantization methods with mixed precision on MobilenetV1/V2, ResNet18 under different resource constraints on the ImageNet dataset.



---

