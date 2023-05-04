# Optimal clipping and magnitude-aware differentiation for improved quantization-aware training

## Summary

Summary: The paper proposes a method called Optimally Clipped Tensors and Vectors (OCTA V) for determining optimal clipping scalars using the fast Newton-Raphson method in quantization-aware training (QAT). The proposed method improves accuracy by reducing noise in quantization operations. The paper also proposes magnitude-aware differentiation to further improve accuracy. Experimental results show that OCTA V-enabled QAT achieves state-of-the-art accuracy on multiple tasks with low precision.


## Target Task

computer vision

## Content

<Abstract:>
Data clipping is proposed as a method to reduce noise in quantization operations and improve accuracy in quantization-aware training (QAT). However, current methods for setting clipping threshold scalars are not optimal. In this paper, the authors propose an algorithm called Optimally Clipped Tensors and Vectors (OCTA V) that recursively determines the optimal clipping scalars using the fast Newton-Raphson method. Additionally, common gradient estimation techniques in QAT are shown to have limitations and magnitude-aware differentiation is proposed to further improve accuracy. Experimental results demonstrate that OCTA V-enabled QAT achieves state-of-the-art accuracy on multiple tasks with low precision (4-to-6-bits) without modifications to the baseline training recipe.



---

