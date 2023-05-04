# Streaming architecture for large-scale quantized neural networks on an FPGA-based dataflow platform

## Summary

<Summary: > This paper introduces a new streaming architecture for running quantized NNs on FPGAs that supports skip connections used in state-of-the-art NNs. This architecture allows for the implementation of an 18-layer ResNet for 224x224 image classification achieving 57.5% top-1 accuracy and a full-sized quantized AlexNet with 2-bit activations instead of 1-bit, improving accuracy from 41.8% to 51.03% for ImageNet classification. The ResNet-18 implementation consumes 5 times less power and is 4 times slower for ImageNet than the same NN on the latest Nvidia GPUs. Smaller Nets that fit a single FPGA run faster than GPUs on inputs of up to 32x32 while consuming up to 20 times less energy and power.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks (DNNs) are widely used in various applications, but their huge footprint and high computational and communication needs put a strain on resources. Low-precision representations of weights and other parameters have been found to achieve similar accuracy while requiring fewer resources. Quantized values enable the use of field-programmable gate arrays (FPGAs) to run neural networks (NNs), as they are well-suited to bitwise operations and arbitrary-precision representation of numbers. This paper presents a new streaming architecture for running quantized NNs on FPGAs, with support for skip connections used in state-of-the-art NNs. The architecture allows for the implementation of an 18-layer ResNet for 224x224 image classification achieving 57.5% top-1 accuracy and a full-sized quantized AlexNet with 2-bit activations instead of 1-bit, improving accuracy from 41.8% to 51.03% for ImageNet classification. The ResNet-18 implementation consumes 5 times less power and is 4 times slower for ImageNet than the same NN on the latest Nvidia GPUs. Smaller Nets that fit a single FPGA run faster than GPUs on inputs of up to 32x32 while consuming up to 20 times less energy and power.



---

