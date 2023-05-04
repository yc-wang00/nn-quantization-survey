# Generative zero-shot network quantization

## Summary

Summary: The paper proposes a method for zero-shot quantization of convolutional neural networks using intrinsic Batch Normalization statistics. The approach generates a calibration set for corresponding zero-shot network quantization by using VAE/GAN methods to match the distribution of BN statistics. The proposed method outperforms existing data-free quantization methods as demonstrated by experiments on benchmark datasets.


## Target Task

computer vision

## Content

<Abstract:>
Convolutional neural networks can generate realistic images with the help of ample training samples. However, in the absence of original training data, zero-shot quantization of such models becomes indispensable. To address this, we leverage intrinsic Batch Normalization (BN) statistics to reconstruct “realistic” images of each category without any training data. Following VAE/GAN methods, we regard the zero-shot optimization of synthetic images as generative modeling to match the distribution of BN statistics, thus generating a calibration set for the corresponding zero-shot network quantizations. Our experiments on benchmark datasets show that our approach consistently outperforms existing data-free quantization methods.



---

