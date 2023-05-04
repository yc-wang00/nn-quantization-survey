# FrostNet: Towards quantization-aware network architecture search

## Summary

Summary: The paper proposes a new network architecture search (NAS) method to find a network that guarantees both full-precision and INT8 performances. The method uses a critical optimization method called Frost bottleneck, which enables quantization-aware training by integrating gradient-based NAS with StatAssist and GradBoost. Using Frost bottleneck as a building block for hardware-aware NAS, the authors discovered FrostNets that show improved quantization performance compared to other mobile-target networks while maintaining FLOAT32 performance.


## Target Task

computer vision

## Content

<Abstract: >
INT8 quantization has become a standard technique for deploying convolutional neural networks on edge devices to reduce memory and computational resource usage. This paper presents a new network architecture search (NAS) procedure to find a network that guarantees both full-precision (FLOAT32) and quantized (INT8) performances. The paper proposes a critical optimization method, Frost bottleneck, which enables quantization-aware training (QAT): floating-point statistic assisting (StatAssist) and stochastic gradient boosting (GradBoost). By integrating gradient-based NAS with StatAssist and GradBoost, the authors discovered a quantization-efficient network building block, Frost bottleneck. Furthermore, FrostNets, which show improved quantization performances compared to other mobile-target networks while maintaining comparable FLOAT32 performance was obtained using Frost bottleneck as the building block for hardware-aware NAS.



---

