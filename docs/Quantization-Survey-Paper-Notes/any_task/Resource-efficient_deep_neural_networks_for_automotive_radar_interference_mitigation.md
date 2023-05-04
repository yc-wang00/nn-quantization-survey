# Resource-efficient deep neural networks for automotive radar interference mitigation

## Summary

<Summary: >The authors investigate quantization techniques for DNN-based denoising and interference mitigation of radar signals to reduce memory requirements. The study compares models with fixed and learned bit-widths, achieving an 80% memory reduction compared to the real-valued baseline. The authors recommend using 8 bits for weights and activations resulting in models that require only 0.2 megabytes of memory.


## Target Task

any task

## Content

<Abstract: >Radar sensors are crucial for environment perception in autonomous vehicles and driver assistance systems. However, with the increasing number of radar sensors and unregulated automotive radar frequency bands, mutual interference is inevitable and must be dealt with. Deep neural networks (DNNs) have emerged for radar spectra denoising and interference mitigation, but they require high memory and computational resources. In this study, the authors investigate quantization techniques for DNN-based denoising and interference mitigation of radar signals to reduce memory requirements for model storage and during inference. They compare models with fixed and learned bit-widths and illustrate the importance of structurally small real-valued base models for quantization. The authors achieve a memory reduction of around 80% compared to the real-valued baseline and recommend the use of 8 bits for weights and activations, which results in models that require only 0.2 megabytes of memory.



---

