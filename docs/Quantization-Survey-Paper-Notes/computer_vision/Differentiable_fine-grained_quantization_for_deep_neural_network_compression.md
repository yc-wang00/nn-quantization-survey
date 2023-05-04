# Differentiable fine-grained quantization for deep neural network compression

## Summary

<Summary: > This paper proposes a fine-grained quantization approach for deep neural network compression by optimizing a mixed-precision quantization scheme. The proposed approach optimizes the search space of quantization bitwidth from discrete to a continuous domain. The approach can potentially produce more efficient models compared to traditional quantization methods by striking a better balance between accuracy and compression rate for different layers/structures. The mixed-precision quantization scheme generated by the proposed approach outperforms the accuracy of traditional quantization methods under the same compression rate.


## Target Task

computer vision

## Content

<Abstract: >Neural networks have shown great performance in cognitive tasks. When deploying
network models on mobile devices with limited resources, weight quantization
has been widely adopted. Binary quantization obtains the highest compression but
usually results in big accuracy drop. In practice, 8-bit or 16-bit quantization is often
used aiming at maintaining the same accuracy as the original 32-bit precision. We
observe different quantization schemes have different accuracy impact on different
layers. Thus judiciously selecting different precision for different layers/structures
can potentially produce more efﬁcient models compared to traditional quantization
methods by striking a better balance between accuracy and compression rate. In
this work, we propose a ﬁne-grained quantization approach for deep neural network
compression by relaxing the search space of quantization bitwidth from discrete
to a continuous domain. The proposed approach applies gradient descend based
optimization to generate a mixed-precision quantization scheme that outperforms
the accuracy of traditional quantization methods under the same compression rate.



---
