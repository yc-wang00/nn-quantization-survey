# Learnable Lookup Table for Neural Network Quantization

## Summary

Summary: This paper proposes a new method for neural network quantization using learnable lookup tables (LLTs), which reduces computational costs in the activation quantization process. The proposed method achieves state-of-the-art performance in various tasks and outperforms existing quantization methods that use pre-defined functions for quantizers.


## Target Task

computer vision

## Content

<Abstract: >Neural network quantization is widely used to reduce the bit-width of weights and activations for efficient memory and computation. However, existing methods with pre-defined functions for quantizers introduce considerable computational overhead in the activation quantization process. This paper proposes the use of learnable lookup tables (LLTs) as quantizers to reduce computational costs. The quantization process is formulated as a simple lookup operation, and LLTs are trained in an end-to-end manner to fit distributions in different layers. The proposed method achieves state-of-the-art performance in image classification, image super-resolution, and point cloud classification tasks when compared with previous methods.



---

