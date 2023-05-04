# It's All In the Teacher: Zero-Shot Quantization Brought Closer to the Teacher

## Summary

Summary: This paper focuses on model quantization, a technique used to reduce the resource requirements of deep neural networks, and proposes a new approach called AIT for zero-shot quantization. The method uses information from a full-precision teacher network to fine-tune the quantized network, addressing the difficulties of optimizing multiple loss terms and poor generalization capability due to synthetic samples of existing methods. Experiments show that AIT outperforms many existing methods and takes over the overall state-of-the-art position in the field.


## Target Task

computer vision

## Content

<Abstract: >Model quantization is considered as a promising method to greatly reduce the resource requirements of deep neural networks. To deal with the performance drop induced by quantization errors, a popular method is to use training data to fine-tune quantized networks. Zero-shot quantization addresses such problems, usually by taking information from the weights of a full-precision teacher network to compensate the performance drop of the quantized networks. This paper analyzes the loss surface of state-of-the-art zero-shot quantization techniques and provides several findings. In contrast to usual knowledge distillation problems, zero-shot quantization often suffers from 1) the difficulty of optimizing multiple loss terms together, and 2) the poor generalization capability due to the use of synthetic samples. Based on the observations, the paper proposes AIT, a simple yet powerful technique for zero-shot quantization, which addresses the aforementioned two problems. Experiments show that AIT outperforms the performance of many existing methods by a great margin, taking over the overall state-of-the-art position in the field.



---

