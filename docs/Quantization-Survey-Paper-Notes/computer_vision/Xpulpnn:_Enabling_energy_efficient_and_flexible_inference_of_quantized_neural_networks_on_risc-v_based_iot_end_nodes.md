# Xpulpnn: Enabling energy efficient and flexible inference of quantized neural networks on risc-v based iot end nodes

## Summary

<Summary: > This paper introduces lightweight extensions to the RISC-V ISA to improve the efficiency of heavily quantized neural network inference on microcontroller-class cores. By extending the ISA with nibble and crumb SIMD instructions, the authors demonstrated near-linear speedup with respect to higher precision integer computation for QNN computation, and a custom execution paradigm for SIMD sum-of-dot-product operations which brings an improvement in peak MAC/cycle. The proposed solution achieves efficiency levels comparable with dedicated DNN inference accelerators and up to three orders of magnitude better than state-of-the-art ARM Cortex-M based microcontroller systems.


## Target Task

computer vision

## Content

<Abstract: >Strongly quantized fixed-point arithmetic is now considered a well-established solution to deploy Convolutional Neural Networks (CNNs) on limited-memory low-power IoT end-nodes. Emerging open-source ISAs such as RISC-V provide a flexible way to address challenges in low bitwidth fixed-point instructions. This work introduces lightweight extensions to the RISC-V ISA to boost the efficiency of heavily quantized neural network (QNN) inference on microcontroller-class cores. By extending the ISA with nibble and crumb SIMD instructions, the authors are able to show near-linear speedup with respect to higher precision integer computation on the key kernels for QNN computation. Additionally, the authors propose a custom execution paradigm for SIMD sum-of-dot-product operations, which consists of fusing a dot product with a load operation, and show an up to 1.64 peak MAC/cycle improvement compared to a standard execution scenario. The proposed solution achieves efficiency levels comparable with dedicated DNN inference accelerators and up to three orders of magnitude better than state-of-the-art ARM Cortex-M based microcontroller systems such as the low-end STM32L4 MCU and the high-end STM32H7 MCU.



---

