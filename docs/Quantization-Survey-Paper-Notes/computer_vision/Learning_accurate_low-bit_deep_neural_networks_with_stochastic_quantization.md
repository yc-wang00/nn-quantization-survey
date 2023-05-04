# Learning accurate low-bit deep neural networks with stochastic quantization

## Summary

<Summary: >The paper introduces the stochastic quantization algorithm for learning accurate low-bit deep neural networks. The algorithm quantizes a portion of elements or filters based on a stochastic probability inversely proportional to the quantization error, while keeping the other portion with full-precision. The accuracy of low-bit DNNs on various datasets and network structures can be improved significantly and consistently using SQ.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes the stochastic quantization (SQ) algorithm for learning accurate low-bit deep neural networks (DNNs). The SQ algorithm quantizes a portion of elements/filters to low-bit with a stochastic probability inversely proportional to the quantization error, while keeping the other portion unchanged with full-precision. The quantized and full-precision portions are updated with corresponding gradients separately in each iteration. Experiments show that SQ can consistently and significantly improve the accuracy for different low-bit DNNs on various datasets and various network structures.



---

