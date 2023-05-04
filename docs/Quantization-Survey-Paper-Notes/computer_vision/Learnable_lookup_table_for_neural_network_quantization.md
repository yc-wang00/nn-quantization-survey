# Learnable lookup table for neural network quantization

## Summary

<Summary: >This paper proposes a method of neural network quantization using learnable lookup tables (LLTs) that can be trained end-to-end, having very minimal computational cost. The approach has been tested on image classification, image super-resolution, and point cloud classification tasks, and it outperforms previous methods.


## Target Task

computer vision

## Content

<Abstract:>
Neural network quantization has gained attention due to its ability to reduce computational and memory footprint. However, quantization error may affect the accuracy of the network. Many methods use pre-defined functions with learnable parameters to reduce quantization error, but these methods introduce considerable computational overhead. In this paper, a look-up operation is proposed for quantization, formulated as learnable lookup tables (LLTs). The LLTs can be trained in an end-to-end manner and have very small additional computational cost. The proposed method achieves state-of-the-art performance on image classification, image super-resolution, and point cloud classification tasks compared to previous methods.



---

