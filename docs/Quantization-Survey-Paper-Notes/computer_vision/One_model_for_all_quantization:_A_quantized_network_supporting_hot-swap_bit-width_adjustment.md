# One model for all quantization: A quantized network supporting hot-swap bit-width adjustment

## Summary

<Summary: > The paper proposes a method for training neural network models that can be effectively used for model quantization of bit-widths ranging from 8-bit to 1-bit. The proposed technique uses multiscale quantization with wavelet decomposition and reconstruction to diversify weights, which leads to significant improvement in performance in ultra-low bit-width situations. The method provides specific quantization strategies to different candidates, which can be hot-swapped, and eliminates the need for fine-tuning the quantized model or minimizing the quantization noise. The experimental results show that the proposed method performs comparably to specialized models previously trained at the same precision in ImageNet and COCO datasets.


## Target Task

computer vision

## Content

<Abstract: > As an effective technique to achieve implementation of deep neural networks on edge devices, model quantization has been successfully applied in many practical applications. In this work, a method is proposed to train a model for all quantization that supports diverse bit-widths (e.g., from 8-bit to 1-bit) to satisfy the online quantization bit-width adjustment without the need for fine-tuning the quantized model or minimizing the quantization noise. The proposed method provides specific quantization strategies for different candidates through multiscale quantization, which is hot-swappable. Wavelet decomposition and reconstruction are used to increase the diversity of weights, thus significantly improving the performance of each quantization candidate, especially at ultra-low bit-widths (e.g., 3-bit, 2-bit, and 1-bit). Experimental results on ImageNet and COCO demonstrate that the proposed method achieves accuracy comparable to that of dedicated models trained at the same precision.



---

