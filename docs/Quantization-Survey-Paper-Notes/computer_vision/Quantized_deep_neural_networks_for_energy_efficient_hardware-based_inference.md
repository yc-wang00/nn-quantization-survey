# Quantized deep neural networks for energy efficient hardware-based inference

## Summary

<Summary: > The paper proposes a novel approach to reduce energy consumption of a DNN by quantizing the weights, activations, and gradients of the neural network. They demonstrate the effectiveness of the proposed quantization method on several benchmark datasets by achieving up to 4x reduction in energy consumption with only minor retraining loss. A hardware architecture is also proposed, which can achieve up to 7x higher energy efficiency compared to the state-of-the-art FPGA-based accelerator for quantized DNNs.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose a novel approach to reduce the energy consumption of deep neural network (DNN) inference by quantizing the weights, activations, and gradients of the neural network. Most previous approaches in the literature focused only on the quantization of weights and activations. Our approach includes quantization of back-propagation gradients which allows for training quantized models in an end-to-end manner. We demonstrate the effectiveness of our proposed quantization method on several benchmark datasets by achieving up to 4x reduction in energy consumption with only minor retraining loss. We also propose a hardware architecture with a datapath tailored for our quantized neural network that can be efficiently implemented on an FPGA platform. Our hardware design can achieve up to 7x higher energy efficiency compared to the state-of-the-art FPGA-based accelerator for quantized DNNs.



---

