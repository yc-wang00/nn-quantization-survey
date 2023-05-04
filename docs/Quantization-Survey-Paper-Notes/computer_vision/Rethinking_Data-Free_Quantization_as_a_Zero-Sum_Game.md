# Rethinking Data-Free Quantization as a Zero-Sum Game

## Summary

<Summary: >This paper proposes a method called Adaptability-aware Sample Generation (AdaSG) for data-free quantization (DFQ) that reformulates DFQ as a zero-sum game between two players: a generator and a quantized network. AdaSG aims to generate a sample with desirable adaptability to maximally recover the performance of the quantized network with varied bit widths.


## Target Task

computer vision

## Content

<Abstract: >Data-free quantization (DFQ) is a potential method to quantize models without accessing the original data by synthesizing meaningful fake samples instead, which improves the quantized network (Q) by knowledge distillation against the pretrained full-precision model (P). The generative model is introduced as a generator (G) to capture the distribution of the original data from P for better fake samples. However, there still remains a non-ignorable performance loss when encountering various bit-width settings. In this paper, we revisit DFQ and specialize it as a zero-sum game between two players - a generator and a quantized network, and further propose an Adaptability-aware Sample Generation (AdaSG) method. AdaSG reformulates DFQ as a dynamic maximization-vs-minimization game process anchored on the sample adaptability, and aims to generate the sample with desirable adaptability to maximally recover the performance of Q with varied bit widths.



---

