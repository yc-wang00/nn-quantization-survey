# Dorefa-net: Training low bitwidth convolutional neural networks with low bitwidth gradients

## Summary

Summary: The paper presents DoReFa-Net, a method to train convolutional neural networks using low bitwidth weights and activations. The proposed method quantizes parameter gradients to low bitwidth numbers during the backward pass and uses bit convolution kernels to accelerate training and inference. The application of bit convolutions enables the efficient implementation of DoReFa-Net in various hardware platforms. The experimental results demonstrate that the proposed method can achieve comparable prediction accuracy with 32-bit counterparts. Notably, a 1-bit weights, 2-bit activations DoReFa-Net derived from AlexNet, using 6-bit gradients, achieved a top-1 accuracy of 46.1% on ImageNet validation set. The code for the DoReFa-Net AlexNet model is available openly.


## Target Task

computer vision

## Content

<Abstract: >
We propose DoReFa-Net, a method to train convolutional neural networks that have low bitwidth weights and activations using low bitwidth parameter gradients. Our method quantizes the parameter gradients to low bitwidth numbers during the backward pass before propagating them to convolutional layers. As convolutions can now operate on low bitwidth weights and activations/gradients respectively, DoReFa-Net can use bit convolution kernels to accelerate both training and inference. Additionally, bit convolutions can be implemented efficiently on CPU, FPGA, ASIC, and GPU, allowing DoReFa-Net to be used for training low bitwidth neural networks on these hardware platforms. Experimental results on SVHN and ImageNet datasets prove that DoReFa-Net can achieve comparable prediction accuracy as 32-bit counterparts. A 1-bit weights, 2-bit activations DoReFa-Net derived from AlexNet can be trained from scratch using 6-bit gradients to achieve a top-1 accuracy of 46.1% on ImageNet validation set. The DoReFa-Net AlexNet model is publicly available.



---

