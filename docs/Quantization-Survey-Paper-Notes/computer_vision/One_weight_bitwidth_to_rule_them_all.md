# One weight bitwidth to rule them all

## Summary

Summary: The paper proposes aligning all weights to the same model size using a width-multiplier to achieve better accuracy compared to mixed-precision quantization with different bitwidths. It suggests that a single weight bitwidth throughout the network shows superior results for model compression.


## Target Task

computer vision

## Content

<Abstract: >Weight quantization is a widely used technique for deep ConvNets to improve the parameter efficiency of ConvNets while maintaining accuracy. However, different tasks may result in different bitwidths for quantization, which creates complexity for software and hardware support. In this paper, we propose to align all weights to the same model size using a width-multiplier, and we show that using a single weight bitwidth throughout the network can achieve better accuracy compared to mixed-precision quantization targeting zero accuracy degradation when both have the same model size. We also suggest that when the number of channels becomes a target hyperparameter, a single weight bitwidth throughout the network shows superior results for model compression.



---

