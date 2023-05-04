# Effective training of convolutional neural networks with low-bitwidth weights and activations

## Summary

<Summary: >This paper introduces three methods for training a convolutional neural network with low-bitwidth weights and activations. These methods include progressive quantization, stochastic precision, and joint knowledge distillation, which are effective in various experiments including CIFAR-100 and ImageNet datasets. The progressive quantization method gradually decreases the bit-width from high to low precision during training, while stochastic precision randomly quantizes sub-networks. Finally, joint knowledge distillation trains a full-precision model alongside the low-precision model for better training guidance.


## Target Task

computer vision

## Content

<Abstract: > This paper proposes three approaches for training a deep convolutional neural network with low-bitwidth weights and activations: progressive quantization, stochastic precision, and joint knowledge distillation. The progressive quantization method involves two schemes for finding good local minima by optimizing a network with quantized weights first and then quantizing activations, and gradually decreasing the bit-width from high-precision to low-precision during training. To alleviate the excessive training burden, stochastic precision randomly samples and quantizes sub-networks while keeping other parts in full-precision. And, joint knowledge distillation trains a full-precision model alongside the low-precision one to provide hints for the low-precision model training. The proposed methods show effectiveness in various experiments on datasets such as CIFAR-100 and ImageNet.



---

