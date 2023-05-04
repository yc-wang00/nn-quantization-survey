# Bayesian bits: Unifying quantization and pruning

## Summary

<Summary: >The paper introduces a practical method for joint mixed precision quantization and pruning through gradient-based optimization called Bayesian Bits. The method uses a sequential doubling of the bit width and quantizes the residual error between the full precision value and the previously rounded value at each stage. The method employs learnable stochastic gates to control the bit width and obtain low bit solutions by performing approximate inference. The experimental results show that the proposed method can learn pruned, mixed precision networks that provide a better trade-off between accuracy and efficiency than their static bit-width equivalents.


## Target Task

computer vision

## Content

<Abstract: >We introduce Bayesian Bits, a practical method for joint mixed precision quantization and pruning through gradient based optimization. Bayesian Bits employs a novel decomposition of the quantization operation, which sequentially considers doubling the bit width. At each new bit width, the residual error between the full precision value and the previously rounded value is quantized. We then decide whether or not to add this quantized residual error for a higher effective bit width and lower quantization noise. By starting with a power-of-two bit width, this decomposition will always produce hardware-friendly configurations, and through an additional 0-bit option, serves as a unified view of pruning and quantization. Bayesian Bits then introduces learnable stochastic gates, which collectively control the bit width of the given tensor. As a result, we can obtain low bit solutions by performing approximate inference over the gates, with prior distributions that encourage most of them to be switched off. We experimentally validate our proposed method on several benchmark datasets and show that we can learn pruned, mixed precision networks that provide a better trade-off between accuracy and efficiency than their static bit width equivalents.



---

