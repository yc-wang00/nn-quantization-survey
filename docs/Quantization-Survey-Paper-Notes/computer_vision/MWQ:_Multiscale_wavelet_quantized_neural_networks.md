# MWQ: Multiscale wavelet quantized neural networks

## Summary

<Summary: >The paper proposes a multiscale wavelet quantization method for deep neural networks, which decomposes original data into multiscale frequency components and quantizes the components of different scales respectively. The proposed method exploits multiscale frequency and spatial information to reduce information loss caused by quantization in the spatial domain. The method has been applied for different applications, and showed stronger representation ability and effectiveness in quantized neural networks.


## Target Task

computer vision

## Content

<Abstract: >Model quantization can reduce the model size and computational latency, it has become an essential technique for the deployment of deep neural networks on resource-constrained hardware (e.g., mobile phones and embedded devices). The existing quantization methods mainly consider the numerical elements of the weights and activation values, ignoring the relationship between elements. The decline of representation ability and information loss usually lead to the performance degradation. Inspired by the characteristics of images in the frequency domain, we propose a novel multiscale wavelet quantization (MWQ) method. This method decomposes original data into multiscale frequency components by wavelet transform, and then quantizes the components of different scales, respectively. It exploits the multiscale frequency and spatial information to alleviate the information loss caused by quantization in the spatial domain. Because of the flexibility of MWQ, we demonstrate three applications (e.g., model compression, quantized network optimization, and information enhancement) on the ImageNet and COCO datasets. Experimental results show that our method has stronger representation ability and can play an effective role in quantized neural networks.



---

