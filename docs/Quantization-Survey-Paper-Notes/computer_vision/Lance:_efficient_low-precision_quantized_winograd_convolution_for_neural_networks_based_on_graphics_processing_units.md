# Lance: efficient low-precision quantized winograd convolution for neural networks based on graphics processing units

## Summary

Summary: This paper proposes an efficient low-precision quantized Winograd convolution algorithm, called LANCE, for accelerating deep convolutional neural networks. By combining the advantages of fast convolution and quantization techniques, LANCE performs efficiently in low-precision computation on graphics processing units. LANCE is tested on representative image classification datasets and shows up to 2.40 improvements in performance over full-precision convolution with trivial accuracy loss.


## Target Task

computer vision

## Content

<Abstract: >Accelerating deep convolutional neural networks has become an active topic and sparked an interest in academia and industry. In this paper, we propose an efficient low-precision quantized Winograd convolution algorithm, called LANCE, which combines the advantages of fast convolution and quantization techniques. By embedding linear quantization operations into the Winograd-domain, the fast convolution can be performed efficiently under low-precision computation on graphics processing units. We test neural network models with LANCE on representative image classification datasets, including SVHN, CIFAR, and ImageNet. The experimental results show that our 8-bit quantized Winograd convolution improves the performance by up to 2.40 over the full-precision convolution with trivial accuracy loss.



---

