# A Learning Framework for n-Bit Quantized Neural Networks Toward FPGAs

## Summary

Summary: The paper proposes a learning framework for n-bit quantized neural networks with weights constrained to power of two which includes a reconstructed gradient function and a novel QNN structure called n-BQ-NN using shift operations suitable for FPGA implementation. The paper introduces a shift vector processing element array to replace all 16-bit multiplications, reducing energy consumption and increasing execution speed. Experiments show that the quantized models of ResNet, DenseNet, and AlexNet can achieve the same accuracy as the original full-precision models, achieving state-of-the-art results compared to typical low-precision QNNs.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes a learning framework for n-bit quantized neural networks (QNNs) with weights constrained to the power of two. The framework includes a reconstructed gradient function to solve the gradient vanishing problem in back-propagation algorithm and a novel QNN structure called n-BQ-NN that uses shift operations to replace multiplication, making it more suitable for FPGA implementation. The paper also introduces a shift vector processing element (SVPE) array to replace all 16-bit multiplications, reducing energy consumption and increasing execution speed. Experiments show that the quantized models of ResNet, DenseNet, and AlexNet can achieve the same accuracy as the original full-precision models. Furthermore, the proposed learning framework can achieve state-of-the-art results compared to typical low-precision QNNs. Index terms include deep learning, quantum neural network, deep compression, and FPGA.



---

