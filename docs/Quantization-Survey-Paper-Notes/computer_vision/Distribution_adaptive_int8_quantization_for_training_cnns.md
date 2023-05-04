# Distribution adaptive int8 quantization for training cnns

## Summary

<Summary: > The paper presents a training framework for convolutional neural networks based on INT8 quantization with Gradient Vectorized Quantization and Magnitude-aware Clipping Strategy. The proposed method achieves almost lossless training accuracy for various computer vision tasks and is superior to state-of-the-art techniques. Additionally, an INT8 kernel is implemented which accelerates the training iteration by over 200% under the latest Turing architecture, demonstrating the method's excellence in training accuracy and speed.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose a novel INT8 quantization training framework for convolutional neural networks that addresses the variability and uncertainty of gradient distribution. We adopt Gradient Vectorized Quantization to quantize the gradient and introduce Magnitude-aware Clipping Strategy to take the magnitudes of gradients into consideration when minimizing the quantization error. Experimental results on various computer vision tasks demonstrate that the proposed method has achieved almost lossless training accuracy for different backbones, which is superior to state-of-the-art techniques. Furthermore, we have implemented an INT8 kernel that can accelerate the training iteration by more than 200% under the latest Turing architecture, thus exhibiting our method's excellence on both training accuracy and speed.



---

