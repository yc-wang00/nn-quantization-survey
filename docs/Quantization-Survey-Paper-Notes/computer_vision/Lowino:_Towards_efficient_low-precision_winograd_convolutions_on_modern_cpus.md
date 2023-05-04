# Lowino: Towards efficient low-precision winograd convolutions on modern cpus

## Summary

<Summary: >The paper proposes LoWino, a post-training quantization technique for reducing precision loss caused by Winograd transformation, to accelerate convolutional neural networks. Results show that LoWino achieves a 2.04× speedup compared to state-of-the-art implementations while maintaining accuracy.


## Target Task

computer vision

## Content

<Abstract: >Low-precision computation is a widely supported method for accelerating convolutional neural networks, but it is not commonly used to speed up Winograd due to the numerical error caused by combining Winograd transformation and quantization. In this paper, the authors propose LoWino, a low-precision Winograd convolution approach based on post-training quantization, which employs a linear quantization method in the Winograd domain to reduce the precision loss caused by transformations. The authors also present an efficient implementation that adequately exploits the capability of low-precision computation on modern CPUs. Experimental results show that LoWino achieves up to 2.04× speedup over state-of-the-art implementations in the vendor library while maintaining the accuracy at a reasonable level.



---

