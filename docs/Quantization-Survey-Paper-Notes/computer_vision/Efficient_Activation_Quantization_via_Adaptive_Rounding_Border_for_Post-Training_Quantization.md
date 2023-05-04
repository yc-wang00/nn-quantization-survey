# Efficient Activation Quantization via Adaptive Rounding Border for Post-Training Quantization

## Summary

Summary: The paper proposes AQuant, a framework that replaces the constant border in post-training quantization (PTQ) with a border function to minimize error in multiplying two numbers and eliminate bias in expected value, resulting in improved model accuracy. AQuant can automatically learn the border function and optimize errors, achieving better results than previous works on ResNet-18 under 2-bit weight and activation PTQ.


## Target Task

computer vision

## Content

<Abstract: >Post-training quantization (PTQ) is a popular technique for deploying deep neural networks (DNNs) on resource-limited devices. Rounding is the primary source of quantization error in PTQ, for which the traditional rounding-to-nearest scheme is used. However, this work shows that optimizing rounding schemes can improve the model accuracy. To deal with this, the authors propose replacing the constant border with a simple border function that can obtain the minimal error for multiplying two numbers and eliminate the bias of its expected value, further benefiting model accuracy. Based on this, they approximate the border function to make the incurred overhead negligible and optimize propagated errors and global errors. They propose their AQuant framework, which can learn the border function automatically, achieving noticeable improvements compared to state-of-the-art works and pushing the accuracy of ResNet-18 up to 60.31% under the 2-bit weight and activation post-training quantization.



---

