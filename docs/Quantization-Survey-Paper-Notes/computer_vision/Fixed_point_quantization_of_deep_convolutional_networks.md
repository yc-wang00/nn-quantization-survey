# Fixed point quantization of deep convolutional networks

## Summary

Summary: The paper proposes a fixed point implementation method for deep convolution networks that reduces computation and model storage resources. The authors suggest a quantizer design and optimize bit-width allocation across DCN layers. In experiments, the fixed point DCNs with optimized bit width allocation show over 20% reduction in model size without any loss in accuracy on CIFAR-10 benchmark. The paper also reports a new state-of-the-art fixed point performance of 6.78% error-rate on CIFAR-10 benchmark and discusses implementation challenges and solutions.


## Target Task

computer vision

## Content

<Abstract: In this research paper, the authors propose a fixed point implementation method for deep convolution networks (DCNs) to reduce computation and model storage resources. They suggest a quantizer design for fixed point implementation of DCNs, and formulate and solve an optimization problem to identify optimal fixed point bit-width allocation across DCN layers. The experiments show that in comparison to equal bit-width settings, the fixed point DCNs with optimized bit width allocation offer >20% reduction in model size without any loss in accuracy on CIFAR-10 benchmark. They also report a new state-of-the-art fixed point performance of 6.78% error-rate on CIFAR-10 benchmark. The authors discuss the challenges in implementing DCNs in fixed point and suggest possible solutions.>



---

