# Mr. BiQ: Post-Training Non-Uniform Quantization based on Minimizing the Reconstruction Error

## Summary

Summary: The paper proposes a non-uniform quantization method called Mr.BiQ which can be used for low bit-width quantization on Transformer models. The method leverages multi-level binarization for weights and allows activations to be represented in various data formats. Mr.BiQ recognizes the quantization parameters as directly and jointly learnable parameters during optimization which shows significant improvements in accuracy on various models.


## Target Task

nlp

## Content

<Abstract: >
Post-training quantization is a technique used to compress neural networks. However, this method has only been discussed in the context of uniform quantization on convolutional neural networks. In this paper, the authors propose a non-uniform quantization method called Mr.BiQ, which allows low bit-width quantization on Transformer models. The authors leverage multi-level binarization for weights, while allowing activations to be represented as various data formats (e.g., INT8, bfloat16, binary-coding, and FP32). Unlike conventional methods, Mr.BiQ recognizes the quantization parameters as directly and jointly learnable parameters during optimization. The proposed quantization scheme is tested on various models, including convolutional neural networks and Transformer models, and shows significant improvement in accuracy.



---

