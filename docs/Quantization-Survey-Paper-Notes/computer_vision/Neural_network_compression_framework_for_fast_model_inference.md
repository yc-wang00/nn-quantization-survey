# Neural network compression framework for fast model inference

## Summary

<Summary: >The paper introduces Neural Network Compression Framework (NNCF), a PyTorch-based framework that implements various network compression methods such as quantization, sparsity, filter pruning, and binarization. These methods allow creating hardware-friendly models that can be efficiently run on general-purpose or specialized deep learning accelerators while maintaining the model's accuracy. This framework can be used with provided training samples or integrated into an existing training code with minimal adaptations.


## Target Task

computer vision

## Content

<Abstract: >We present a new PyTorch-based framework for neural network compression with ﬁne-tuning named Neural Network Compression Framework (NNCF). It leverages recent advances of various network compression methods and implements some of them, namely quantization, sparsity, ﬁlter pruning and binarization. These methods allow producing more hardware-friendly models that can be eﬃciently run on general-purpose hardware computation units (CPU, GPU) or specialized deep learning accelerators. We show that the implemented methods and their combinations can be successfully applied to a wide range of architectures and tasks to accelerate inference while preserving the original model’s accuracy. The framework can be used in conjunction with the supplied training samples or as a standalone package that can be seamlessly integrated into the existing training code with minimal adaptations.



---

