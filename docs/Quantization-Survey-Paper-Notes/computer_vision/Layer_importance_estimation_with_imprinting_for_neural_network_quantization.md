# Layer importance estimation with imprinting for neural network quantization

## Summary

Summary: The paper proposes an accuracy-aware criterion for quantization of neural networks instead of using fixed low bit-width representation. It proposes mixed-precision quantization on a per-layer basis that requires careful tuning to maintain accuracy while achieving further compression and higher granularity. Additionally, the method suggests the use of imprinting per layer that acts as a proxy module for accuracy estimation in an efficient way.


## Target Task

computer vision

## Content

<Abstract:>
Neural network quantization has achieved a high compression rate using fixed low bit-width representation of weights and activations while maintaining the accuracy of the high-precision original network. However, mixed precision (per-layer bit-width precision) quantization requires careful tuning to maintain accuracy while achieving further compression and higher granularity than fixed-precision quantization. We propose an accuracy-aware criterion to quantify the layer's importance rank. Our method applies imprinting per layer which acts as a proxy module for accuracy estimation in an efficient way.



---

