# Lightweight compression of neural network feature tensors for collaborative intelligence

## Summary

Summary: This paper proposes a lightweight compression method for compressing the activations of a split deep neural network layer in collaborative intelligence applications. The method uses simple and coarse scalar quantization, clipping, binarization, and entropy coding without requiring any retraining. A modified entropy-constrained quantizer design algorithm is also presented. The proposed method was able to compress the 32-bit floating point activations down to 0.6 to 0.8 bits while maintaining accuracy within 1%. The method's performance and simplicity make it a suitable option for coding layer activations in split neural networks for edge/cloud applications.


## Target Task

Target: Computer Vision.

## Content

<Abstract:>
This paper presents a lightweight compression technique for coding the activations of a split deep neural network (DNN) layer in collaborative intelligence applications. The proposed method uses simple and coarse scalar quantization along with clipping, binarization, and entropy coding to compress the activations without requiring any retraining. A modified entropy-constrained quantizer design algorithm optimized for clipped activations is also presented. When applied to popular object-detection and classification DNNs, the proposed compression method was able to compress the 32-bit floating point activations down to 0.6 to 0.8 bits, while keeping the loss in accuracy to less than 1%. Comparisons to compressions using the HEVC screen content coding extension were also presented. The performance and simplicity of this lightweight compression technique make it an attractive option for coding a layer’s activations in split neural networks for edge/cloud applications.



---

