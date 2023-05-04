# QGTC: Accelerating Quantized Graph Neural Networks via GPU Tensor Core

## Summary

<Summary: >The paper proposes QGTC, a Tensor Core-based computing framework that supports any-bitwidth computation for quantized graph neural networks (QGNNs) on GPUs. The authors introduced a novel quantized low-bit arithmetic design, TC-tailored CUDA kernel design, and an effective bandwidth-optimized subgraph packing strategy to maximize transferring efficiency. QGTC integrated with Pytorch, achieving evident inference speedup compared to the state-of-the-art DGL framework across diverse settings.


## Target Task

computer vision

## Content

<Abstract: >Over the most recent years, quantized graph neural network(QGNN) attracts lots of research and industry attention due to its high robustness and low computation and memory overhead. Unfortunately, the performance gains of QGNN have never been realized on modern GPU platforms. To this end, we propose the first Tensor Core (TC) based computing framework, QGTC, to support any-bitwidth computation for QGNNs on GPUs. We introduce a novel quantized low-bit arithmetic design based on the low-bit data representation and bit-decomposed computation. We craft a novel TC-tailored CUDA kernel design by incorporating 3D-stacked bit compression, zero-tile jumping, and non-zero tile reuse technique to improve the performance systematically. We incorporate an effective bandwidth-optimized subgraph packing strategy to maximize the transferring efficiency between CPU host and GPU device. We integrate QGTC with Pytorch for better programmability and extensibility. Extensive experiments demonstrate that QGTC can achieve evident inference speedup (on average 2.7×) compared with the state-of-the-art DGL framework across diverse settings.



---

