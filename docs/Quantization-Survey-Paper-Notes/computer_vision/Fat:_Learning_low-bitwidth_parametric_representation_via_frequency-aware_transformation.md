# Fat: Learning low-bitwidth parametric representation via frequency-aware transformation

## Summary

<Summary: >The paper presents a new quantization pipeline called Frequency-Aware Transformation (FAT), which transforms network weights in the frequency domain before quantization, improving the performance of low bitwidth CNNs, without the need for hyper-parameter tuning. FAT is shown to improve both uniform and non-uniform quantizers, can be easily implemented in various CNN architectures, and outperforms recent state-of-the-art models by reducing computations by 54.9% and 45.7% against full-precision models.


## Target Task

computer vision

## Content

<Abstract: >Learning convolutional neural networks (CNNs) with low bitwidth is challenging because performance may drop significantly after quantization. In this work, a novel quantization pipeline called Frequency-Aware Transformation (FAT) is presented, which learns to transform network weights in the frequency domain before quantization, making them more amenable to training in low bitwidth. CNNs can be easily trained in low precision using simple standard quantizers without tedious hyper-parameter tuning. Theoretical analysis shows that FAT improves both uniform and non-uniform quantizers. FAT can be easily plugged into many CNN architectures, and it outperforms recent state-of-the-art by reducing 54.9% and 45.7% computations against full-precision models.



---

