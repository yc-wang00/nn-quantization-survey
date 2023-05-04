# From Quantized DNNs to Quantizable DNNs

## Summary

<Summary: > This paper introduces the concept of Quantizable DNNs which can quantize its bit-width during execution without re-training. The proposed consistency-based loss optimizes all bit modes and Bit-Specific Batch Normalization reduces conflicts among different bit modes. Experimental results on CIFAR100 and ImageNet show that Quantizable DNNs are more flexible and achieve higher classification accuracy. Additionally, the consistency-based loss improves the model's generalization performance.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes Quantizable DNNs, a special type of DNNs that can flexibly quantize its bit-width during execution without further re-training. To optimize for all bit modes, a combination loss of all bit modes is proposed which enforces consistent predictions ranging from low-bit mode to 32-bit mode. Because outputs of matrix multiplication in different bit modes have different distributions, Bit-Specific Batch Normalization is introduced to reduce conflicts among different bit modes. Experimental results on CIFAR100 and ImageNet have shown that compared to quantized DNNs, Quantizable DNNs have much better flexibility and achieve even higher classification accuracy. The regularization through the consistency-based loss indeed improves the model's generalization performance.



---

