#  -Norm Batch Normalization for Efficient Training of Deep Neural Networks

## Summary

<Summary: >This paper proposes L1-norm batch normalization (L1BN), which involves only linear operations in training and is approximately equivalent to the conventional L2-norm BN (L2BN) by multiplying a scaling factor that equals to/radicalbigπ2. L1BN maintains the same performance and convergence rate as L2BN, but with higher computational efficiency. Experiment results show that on various convolutional neural networks (CNNs) and generative adversarial networks (GANs), L1BN achieves 25% speedup and 37% energy saving compared to the original L2BN in real ASIC synthesis with reduced resources.


## Target Task

computer vision

## Content

<Abstract: >Batch normalization (BN) is widely used for accelerating and improving the training of deep neural networks (DNNs), but it brings in additional calculations, consumes more memory, and significantly slows down the training iteration. This work proposes L1-norm batch normalization (L1BN), which involves only linear operations in both forward and backward propagation during training, and is approximately equivalent to the conventional L2-norm BN (L2BN) by multiplying a scaling factor that equals to/radicalbigπ2. Experiments on various convolutional neural networks (CNNs) and generative adversarial networks (GANs) show that L1BN maintains the same performance and convergence rate as L2BN, but with higher computational efficiency. In real ASIC synthesis with reduced resources, L1BN achieves 25% speedup and 37% energy saving compared to the original L2BN.



---

