# Towards effective low-bitwidth convolutional neural networks

## Summary

Summary: This paper proposes three methods to improve the training of a low-precision convolutional neural network using low-precision weights and low-bitwidth activations. The approaches include a two-stage optimization strategy, a progressive optimization approach, and a novel learning scheme. The methods demonstrated to be effective in different datasets, with a 4-bit precision network performing comparable to full-precision models using standard architectures like AlexNet and ResNet-50.


## Target Task

computer vision

## Content

<Abstract:>
This paper proposes three approaches to improve the training of a low-precision convolutional neural network with both low-precision weights and low-bitwidth activations. First, a two-stage optimization strategy is proposed to optimize a net with quantized weights followed by quantized activations. Second, a progressive optimization approach is used to decrease bit-width from high-precision to low-precision during the training process. Finally, a novel learning scheme is adopted to jointly train a full-precision model alongside the low-precision one to provide guidance. The proposed methods are shown to be effective in experiments on various datasets, with a 4-bit precision network achieving performance comparable to its full-precision counterpart using standard network architectures (i.e., AlexNet and ResNet-50).



---

