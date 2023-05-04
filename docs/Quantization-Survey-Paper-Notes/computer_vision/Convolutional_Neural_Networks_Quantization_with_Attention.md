# Convolutional Neural Networks Quantization with Attention

## Summary

Summary: The paper discusses the benefits of quantizing deep convolutional neural networks (DCNNs) for embedded devices with limited memory and computing resources. The authors propose a double-stage Squeeze-and-Threshold (double-stage ST) activation quantization method that uses the attention mechanism to achieve improved accuracy. The method is easy to apply and achieves state-of-the-art results, surpassing the accuracy of the full-precision baseline model. The paper compares the proposed method with previous works and concludes that it is a promising approach for quantizing DCNNs. Keywords include quantization, attention, and convolutional neural networks.


## Target Task

computer vision

## Content

<Abstract: >It has been proposed that deep convolutional neural networks (DCNNs) can operate with low precision during inference, thereby saving memory space and power consumption, compared to using 32-bit floating-point numbers in the training phase. However, quantizing networks is always accompanied by a decrease in accuracy. In this paper, the authors propose a method, called double-stage Squeeze-and-Threshold (double-stage ST), which uses the attention mechanism to quantize networks and achieve improved accuracy. Using this method, the 3-bit model can achieve accuracy that exceeds the accuracy of the full-precision baseline model. The proposed double-stage ST activation quantization is easy to apply by inserting it before the convolution. The paper discusses network quantization and the benefits it offers for embedded devices that run neural networks with limited memory and computing resources. The authors compare their method with previous works and explain the success of the attention mechanism on CNNs. The proposed method achieves state-of-art results and provides a promising approach for quantizing deep neural networks. The paper concludes with keywords such as quantization, attention, and convolutional neural networks.



---

