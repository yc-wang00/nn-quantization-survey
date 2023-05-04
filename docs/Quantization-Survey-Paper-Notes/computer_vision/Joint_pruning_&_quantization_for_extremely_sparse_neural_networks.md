# Joint pruning & quantization for extremely sparse neural networks

## Summary

<Summary: > The paper proposes a two-stage pruning and quantization pipeline for deep neural networks to achieve extreme sparsity for low cost and low power accelerator hardware. The pipeline includes a Taylor Score and a new fine-tuning mode, which alone showed superior results compared to the state-of-the-art when applied to ResNet on CIFAR10 and ImageNet. The pruning stage can cut up to 99% of memory demand and reduce hardware costs up to 99.9%.


## Target Task

computer vision

## Content

<Abstract: >
We investigate pruning and quantization for deep neural networks, specifically for stereo depth estimation, with the goal of achieving extreme sparsity for quantized networks to enable implementation on low cost and low power accelerator hardware. We propose a two-stage pruning and quantization pipeline with a Taylor Score and a new fine-tuning mode to achieve extreme sparsity without sacrificing performance. Our evaluation demonstrates that our pruning stage alone beats the state-of-the-art when applied to ResNet on CIFAR10 and ImageNet. Almost 99% of memory demand can be cut while hardware costs can be reduced up to 99.9%.



---

