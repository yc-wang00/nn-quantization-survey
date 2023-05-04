# Memory requirement reduction of deep neural networks for field programmable gate arrays using low-bit quantization of parameters

## Summary

Summary: This paper proposes a method that uses non-uniform fixed-point quantization and virtual bit shift to improve the accuracy of quantization of deep neural network weights. The method is tested in a speech enhancement application where a fully connected DNN is used. The low-bit quantization method reduces DNN memory requirements by 50% while STOI performance only drops by 2.7%.


## Target Task

speech recognition

## Content

<Abstract: >Effective employment of deep neural networks (DNNs) in mobile devices and embedded systems, like field programmable gate arrays, is hampered by requirements for memory and computational power. In this paper we propose a method that employs a non-uniform fixed-point quantization and a virtual bit shift (VBS) to improve the accuracy of the quantization of the DNN weights. We evaluate our method in a speech enhancement application, where a fully connected DNN is used to predict the clean speech spectrum from the input noisy speech spectrum. A DNN is optimized, its memory requirement is calculated, and its performance is evaluated using the short-time objective intelligibility (STOI) metric. The application of the low-bit quantization leads to a 50% reduction of the DNN memory requirement while the STOI performance drops only by 2.7%.



---

