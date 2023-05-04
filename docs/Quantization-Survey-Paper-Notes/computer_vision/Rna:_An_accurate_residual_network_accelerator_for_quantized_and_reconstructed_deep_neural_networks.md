# Rna: An accurate residual network accelerator for quantized and reconstructed deep neural networks

## Summary

Summary: The paper introduces a quantized and reconstructed deep neural network technique called QR-DNN, which adds batch normalization (BN) layers during training and later removes them for efficient hardware implementation. It also presents a residual network accelerator (RNA) that utilizes batch-normalization-free structures and logarithmic number system for weights. RNA uses a systolic array architecture for shift-and-accumulate operations instead of multiplication operations, and is reported to have the best fixed-point accelerators. The proposed techniques result in improved accuracy and an FPGA implementation of ResNet-50 achieves state-of-the-art results.


## Target Task

computer vision

## Content

<Abstract: With the continuous refinement of Deep Neural Networks (DNNs), Residual Networks (ResNets) have been widely adopted in state-of-the-art studies. However, the structural complexity and computational cost of ResNets make hardware implementation difficult. In this paper, a quantized and reconstructed deep neural network (QR-DNN) technique is presented, which first inserts batch normalization (BN) layers in the network during training, and later removes them to facilitate efficient hardware implementation. An accurate and efficient residual network accelerator (RNA) is also presented based on QR-DNN with batch-normalization-free structures and weights represented in a logarithmic number system. RNA employs a systolic array architecture to perform shift-and-accumulate operations instead of multiplication operations. The proposed techniques achieve improved accuracy over existing methods and RNA is reported to have the best fixed-point accelerators. An FPGA implementation of ResNet-50 achieves state-of-the-art results.>



---

