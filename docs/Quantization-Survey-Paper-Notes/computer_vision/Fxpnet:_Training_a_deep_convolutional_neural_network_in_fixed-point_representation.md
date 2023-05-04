# Fxpnet: Training a deep convolutional neural network in fixed-point representation

## Summary

Summary: FxpNet is a framework that trains deep convolutional neural networks with low bit-width arithmetics in both forward and backward passes. It adapts the fixed-point formats of stored parameters during training, thus reducing their bit-width. FxpNet includes Integer Batch Normalization (IBN) and Fixed-point ADAM (FxpADAM) to further minimize the floating-point operations. Overall, it achieves comparable prediction accuracy with state-of-the-art binarized and quantized neural networks on the CIFAR-10 dataset with 12-bit primal parameters and 12-bit gradients.


## Target Task

computer vision

## Content

<Abstract:>
We introduce FxpNet, a framework for training deep convolutional neural networks with low bit-width arithmetics in both forward pass and backward pass. FxpNet reduces the bit-width of stored parameters by adaptively updating their fixed-point formats during training. In FxpNet, during forward pass fixed-point primal weights and activations will first be binarized before computation, while in backward pass all gradients are represented as low resolution fixed-point values and then accumulated to corresponding fixed-point primal parameters. FxpNet introduces Integer Batch Normalization (IBN) and Fixed-point ADAM (FxpADAM) methods to further reduce the required floating-point operations. Evaluation on the CIFAR-10 dataset indicates that FxpNet with 12-bit primal parameters and 12-bit gradients achieves comparable prediction accuracy with state-of-art binarized and quantized neural networks.



---

