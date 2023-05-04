# Post-Training Sparsity-Aware Quantization

## Summary

Summary: This paper proposes a method called SPARQ for reducing computational and hardware resources required to run deep neural networks without significant accuracy degradation. SPARQ uses unstructured and dynamic activation sparsity in different representation granularities, such as employing 4-bit quantization by dynamically examining the bits of 8-bit values and choosing a window of 4 bits, and quantizing pairs of 8-bit activations with one equal to zero by opportunistically using the other's 4-bit budget. The method achieves minor accuracy degradation and can be implemented in hardware, making it a promising alternative to traditional quantization methods.


## Target Task

computer vision

## Content

<Abstract: >
In this paper, a sparsity-aware quantization method (SPARQ) is proposed as an alternative to traditional post-training uniform quantization (PTQ) methods for reducing computational and hardware resources required to run deep neural networks (DNNs), while minimizing accuracy degradation. SPARQ leverages unstructured and dynamic activation sparsity in different representation granularities, such as employing 4-bit quantization by dynamically examining the bits of 8-bit values and choosing a window of 4 bits, and quantizing pairs of 8-bit activations with one equal to zero by opportunistically using the other's 4-bit budget. SPARQ achieves minor accuracy degradation and can be practically implemented in hardware, making it a promising alternative to traditional PTQ methods.



---

