# Flexor: Trainable fractional quantization

## Summary

Summary: The paper proposes an encryption algorithm to compress quantized weights by achieving fractional numbers of bits per weight. This method is applied to neural network models using digital XOR-gate networks described using tanh(x) for backward propagation. The proposed method yields higher model accuracy compared to binary neural networks on MNIST, CIFAR-10, and ImageNet datasets with high accuracy even for fractional sub 1-bit weights.


## Target Task

computer vision

## Content

<Abstract:>
Quantization based on binary codes is becoming popular for efficient computations in deep neural networks. However, only allowing for integer numbers of quantization bits limits search space for compression ratio and accuracy. In this paper, we propose an encryption algorithm to compress quantized weights to achieve fractional numbers of bits per weight. Decryption during inference uses digital XOR-gate networks added to the neural network model. XOR gates are described using tanh(x) for backward propagation to enable gradient calculations. The proposed method yields smaller size and higher model accuracy compared to binary neural networks. Experiments using MNIST, CIFAR-10, and ImageNet datasets demonstrate high accuracy even for fractional sub 1-bit weights.



---

