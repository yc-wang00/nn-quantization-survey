# Xnor-net++: Improved binary neural networks

## Summary

<Summary: >The paper presents an improved training algorithm for binary neural networks that combines the scaling factors of weights and activations into a single factor. This factor is learned discriminatively through backpropagation, and its shape is constructed in a few different ways while keeping the computational budget the same. The approach outperforms XNOR-Net in accuracy up to 6% within the same computational budget and is tested on the challenging task of ImageNet classification.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes an improved training algorithm for binary neural networks in which both weights and activations are binary numbers. The authors argue that analytic calculation of the real-valued scaling factors used in the current state-of-the-art method of XNOR-Net is sub-optimal. Instead, the authors propose to fuse the activation and weight scaling factors into a single one that is learned discriminatively via backpropagation. They also explore several ways of constructing the shape of the scale factors while keeping the computational budget fixed, and empirically measure the accuracy of their approximations. They show that their approach significantly outperforms XNOR-Net within the same computational budget when tested on the challenging task of ImageNet classification, offering up to 6% accuracy gain.



---

