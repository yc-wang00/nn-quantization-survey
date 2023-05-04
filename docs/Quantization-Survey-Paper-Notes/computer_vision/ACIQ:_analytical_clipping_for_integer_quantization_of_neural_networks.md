# ACIQ: analytical clipping for integer quantization of neural networks

## Summary

Summary: The paper proposes a method to minimize quantization effects at the tensor level rather than the network level. The authors analyze the trade-off between quantization noise and clipping distortion in low precision networks, identify tensor statistics, and derive approximate analytical expressions for mean-square-error degradation due to clipping. By optimizing these expressions, they show significant improvements over standard quantization schemes, and provide applications for training and inference of low-precision neural networks.


## Target Task

computer vision

## Content

<Abstract: > Unlike traditional approaches that focus on the quantization at the network level, in this work we propose to minimize the quantization effect at the tensor level. We analyze the trade-off between quantization noise and clipping distortion in low precision networks. We identify the statistics of various tensors, and derive approximate analytical expressions for the mean-square-error degradation due to clipping. By optimizing these expressions, we show marked improvements over standard quantization schemes that normally avoid clipping. For example, just by choosing the accurate clipping values, more than 40% accuracy improvement is obtained for the quantization of VGG16-BN to 4-bits of precision. Our results have many applications for the quantization of neural networks at both training and inference time. One immediate application is for a rapid deployment of neural networks to low-precision accelerators without time-consuming fine-tuning or the availability of the full datasets.



---

