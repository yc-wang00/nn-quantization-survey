# Quantization of deep neural networks for accumulator-constrained processors

## Summary

<Summary: >The paper introduces a quantization methodology to enable fixed-point deployment of ANNs without wide accumulation registers. The quantization problem is aimed at maximizing model accuracy by maximizing input data and weights bit widths. The paper suggests 16-bit accumulators can achieve classification accuracy within 1% of floating-point baselines on image classification benchmarks, leading to a near-optimal 2-speedup for image classification.


## Target Task

computer vision

## Content

<Abstract: > We introduce a quantization methodology for Artificial Neural Networks (ANNs), aimed at fixed-point model deployment on embedded compute platforms without wide accumulation registers, i.e. accumulator-constrained processors. The quantization problem is formulated as a function of accumulator size, aiming to maximize model accuracy by maximizing bit widths of input data and weights. Solutions that fully utilize the available accumulator bits are being tested to reduce the number of configurations considered. Performance tests demonstrate that 16-bit accumulators can achieve classification accuracy within 1% of floating-point baselines on image classification benchmarks. Additionally, a near-optimal 2-speedup is obtained by exploiting 16-bit accumulators for image classification on the All-CNN-C and AlexNet networks.



---

