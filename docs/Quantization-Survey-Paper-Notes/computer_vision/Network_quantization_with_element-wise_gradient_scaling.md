# Network quantization with element-wise gradient scaling

## Summary

<Summary: > The paper proposes an alternative method to the straight-through estimator (STE) for network quantization called element-wise gradient scaling (EWGS). The authors adjust a scaling factor adaptively using Hessian information of a network and show experimental results on image classification datasets with diverse network architectures under a wide range of bit-width settings, demonstrating the effectiveness of their method.


## Target Task

computer vision

## Content

<Abstract: > Network quantization aims to reduce the bit-widths of weights and/or activations to implement deep neural networks with limited hardware resources. In this paper, the authors propose an alternative to the straight-through estimator (STE) called element-wise gradient scaling (EWGS), which trains a quantized network better than the STE in terms of stability and accuracy. They adjust a scaling factor adaptively using Hessian information of a network and show experimental results on image classification datasets with diverse network architectures under a wide range of bit-width settings, demonstrating the effectiveness of their method.



---

