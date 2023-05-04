# Quantization-guided training for compact TinyML models

## Summary

Summary: The paper proposes a method called Quantization Guided Training (QGT) to guide DNN training towards optimized low-bit-precision targets, and reach extreme compression levels below 8-bit precision. QGT uses customized regularization to encourage weight values towards a distribution that maximizes accuracy while reducing quantization errors. The effectiveness of QGT is demonstrated using state-of-the-art model architectures (MobileNet, ResNet) on vision datasets and an 81KB tiny model for person detection down to 2-bit precision (representing 17.7x size reduction) while maintaining an accuracy drop of only 3% compared to a floating-point baseline.


## Target Task

computer vision

## Content

<Abstract: >
We address the methodology to train and quantize deep neural networks (DNNs) in order to produce compact models while maintaining algorithmic accuracy. In this paper, we propose a Quantization Guided Training (QGT) method to guide DNN training towards optimized low-bit-precision targets, and reach extreme compression levels below 8-bit precision. Unlike standard quantization-aware training (QAT) approaches, QGT uses customized regularization to encourage weight values towards a distribution that maximizes accuracy while reducing quantization errors. We validate QGT using state-of-the-art model architectures (MobileNet, ResNet) on vision datasets. We also demonstrate the effectiveness with an 81KB tiny model for person detection down to 2-bit precision (representing 17.7x size reduction), while maintaining an accuracy drop of only 3% compared to a floating-point baseline.



---

