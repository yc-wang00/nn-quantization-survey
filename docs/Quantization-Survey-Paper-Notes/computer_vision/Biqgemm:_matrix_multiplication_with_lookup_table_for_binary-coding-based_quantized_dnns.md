# Biqgemm: matrix multiplication with lookup table for binary-coding-based quantized dnns

## Summary

<Summary: > This paper proposes a new matrix multiplication method, BiQGEMM, specifically designed for quantized deep neural networks. The method allows for the simultaneous access of multiple quantized weights in a single instruction, resulting in higher performance than traditional schemes when DNNs are quantized. The paper highlights the benefit of quantization in reducing computations and memory requirements in DNNs.


## Target Task

computer vision

## Content

<Abstract: >The number of parameters in deep neural networks (DNNs) is rapidly increasing to support complicated tasks and improve model accuracy. Correspondingly, the amount of computations and required memory footprint increase as well. Quantization is an efficient method to address such concerns by compressing DNNs such that computations can be simplified while required storage footprint is significantly reduced. In this paper, we propose a novel matrix multiplication method, called BiQGEMM, dedicated to quantized DNNs. BiQGEMM can access multiple quantized weights simultaneously in one instruction. Our extensive experimental results show that BiQGEMM presents higher performance than conventional schemes when DNNs are quantized.



---

