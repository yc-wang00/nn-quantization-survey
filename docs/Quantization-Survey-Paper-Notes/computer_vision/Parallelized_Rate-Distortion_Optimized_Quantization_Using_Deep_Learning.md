# Parallelized Rate-Distortion Optimized Quantization Using Deep Learning

## Summary

<Summary: > This work proposes a neural network-based approach to address the limitations of Rate-Distortion Optimized Quantization (RDOQ) algorithms in real-time hardware encoders. The approach focuses on learning to trade-off rate and distortion during offline supervised training, and it yields a significant reduction in bit-rate with small increases in distortion. The neural network-based approach uses standard arithmetic operations that can be executed on existing neural network hardware, and it does not require additional area-on-chip for dedicated RDOQ circuitry. The evaluation of two classes of neural networks, fully-convolutional and auto-regressive, as post-quantization steps show that they reach 45% of the performance of the iterative HM RDOQ algorithm and achieve 1.64% BD-rate savings on luminosity compared to the HM scalar quantization (SQ) anchor.


## Target Task

computer vision

## Content

<Abstract: >Rate-Distortion Optimized Quantization (RDOQ) has played an important role in the coding performance of recent video compression standards such as H.264/A VC, H.265/HEVC, VP9 and A V1. This scheme yields significant reductions in bit-rate at the expense of relatively small increases in distortion. Typically, RDOQ algorithms are prohibitively expensive to implement on real-time hardware encoders due to their sequential nature and their need to frequently obtain entropy coding costs. This work addresses this limitation using a neural network-based approach, which learns to trade-off rate and distortion during offline supervised training. As these networks are based solely on standard arithmetic operations that can be executed on existing neural network hardware, no additional area-on-chip needs to be reserved for dedicated RDOQ circuitry. We train two classes of neural networks, a fully-convolutional network and an auto-regressive network , and evaluate each as a post-quantization step designed to refine cheap quantization schemes such as scalar quantization (SQ). Both network architectures are designed to have a low computational overhead. After training they are integrated into the HM 16.20 implementation of HEVC, and their video coding performance is evaluated on a subset of the H.266/VVC SDR common test sequences. Comparisons are made to RDOQ and SQ implementations in HM 16.20. Our method achieves 1.64% BD-rate savings on luminosity compared to the HM SQ anchor, and on average reaches 45% of the performance of the iterative HM RDOQ algorithm.



---

