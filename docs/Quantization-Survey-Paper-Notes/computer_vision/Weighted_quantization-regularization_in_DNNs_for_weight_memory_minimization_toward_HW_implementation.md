# Weighted quantization-regularization in DNNs for weight memory minimization toward HW implementation

## Summary

<Summary: >The paper proposes weight quantization to optimize weight memory while converting weights to hardware-friendly data types to deploy neural networks on hardware platforms with limited memory and computational power. Dynamic fixed point and power-of-two quantization techniques are combined with layer-wise precision scaling and quantization-aware fine-tuning. Different bit-widths are allowed for each layer, and retraining for Po2 quantization allows for higher compression rates. The approach achieves compression ratios of 7.34 for CIFAR-10, 4.7 for CIFAR-100, and 9.33 for SVHN with accuracy degradation of only 0.10% points, as verified on an all-convolutional network.


## Target Task

computer vision

## Content

<Abstract: >Deployment of deep neural networks on hardware platforms is often constrained by limited on-chip memory and computational power. The proposed weight quantization offers the possibility of optimizing weight memory alongside transforming the weights to hardware friendly data types. We apply dynamic fixed point (DFP) and power-of-two (Po2) quantization in conjunction with layer-wise precision scaling to minimize the weight memory. To alleviate accuracy degradation due to precision scaling, we employ quantization-aware fine-tuning. For fine-tuning, quantization-regularization (QR) and weighted QR are introduced to force the trained quantization by adding the distance of the weights to the desired quantization levels as a regularization term to the loss-function. While DFP quantization performs better when allowing different bit-widths for each layer, Po2 quantization in combination with retraining allows higher compression rates for equal bit-width quantization. The techniques are verified on an all-convolutional network. With accuracy degradation of 0.10% points, for DFP with layer-wise precision scaling we achieve compression ratios of 7.34 for CIFAR-10, 4.7 for CIFAR-100, and 9.33 for SVHN dataset. Index Terms —Convolutional neural networks, memory minimization, quantization, regularization.



---

