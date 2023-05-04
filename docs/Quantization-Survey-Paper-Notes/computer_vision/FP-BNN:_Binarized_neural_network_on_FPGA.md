# FP-BNN: Binarized neural network on FPGA

## Summary

<Summary: >The paper presents an optimized binarized neural network (BNN) for FPGAs called FP-BNN. The authors use a Resource-Aware Model Analysis (RAMA) method to improve hardware consumption and maintain accuracy. They remove bottlenecks by using bit-level XNOR and shifting operations, as well as data quantization and on-chip storage optimization. The FP-BNN designs showed a Tera operations per second inference performance with acceptable accuracy for MNIST MLP, Cifar-10 ConvNet, and AlexNet on a Stratix-V FPGA system.


## Target Task

computer vision

## Content

<Abstract: > This paper presents FP-BNN, a binarized neural network (BNN) for FPGAs, which significantly reduces hardware consumption while maintaining acceptable accuracy. The authors introduce a Resource-Aware Model Analysis (RAMA) method and remove bottlenecks involving multipliers by bit-level XNOR and shifting operations, as well as the bottleneck of parameter access by data quantization and optimized on-chip storage. They evaluate the FP-BNN accelerator designs for MNIST multi-layer perceptrons (MLP), Cifar-10 ConvNet, and AlexNet on a Stratix-V FPGA system. An inference performance of Tera operations per second with acceptable accuracy loss is obtained.



---

