# Finite alphabet iterative decoding of LDPC codes with coarsely quantized neural networks

## Summary

Summary: This paper presents a method of using Quantized Neural Networks (QNN) to design Finite Alphabet Message Passing Decoders (FAID) for Low-Density Parity Check (LDPC) codes. The authors train these networks to minimize the bit error rate by using straight-through estimators (STE) to handle the zero derivatives. The simulations show that training a QNN can obtain a FAID with 3-bit message and 4-bit channel output, which performs better than the floating-point min-sum decoding algorithm while maintaining good error performance in a flexible and efficient manner.


## Target Task

speech recognition

## Content

<Abstract: >In this paper, the authors introduce a method of using quantized neural networks (QNN) to design finite alphabet message passing decoders (FAID) for Low-Density Parity Check (LDPC) codes. They train such networks while minimizing the bit error rate, which is a widely used and accurate metric to measure the performance of iterative decoders. They use straight-through estimators (STE) to handle the zero derivatives in the backward propagation caused by the low precision activations. Examples and simulations show that by training a QNN, a FAID with 3-bit of message and 4-bit of channel output can be obtained, which performs better than the more complex floating-point min-sum decoding algorithm. This methodology is promising in the sense that it facilitates designing low-precision FAID for LDPC codes while maintaining good error performance in a flexible and efficient manner.



---

