# SYMOG: Learning symmetric mixture of Gaussian modes for improved fixed-point quantization

## Summary

<Summary: >The paper proposes a new method called SYMOG for soft quantization to reduce the complexity of deep neural networks (DNNs) through low-bit fixed-point quantization. The proposed method involves changing the weight distribution from a unimodal Gaussian distribution to a symmetric mixture of Gaussians where each mean value belongs to a fixed-point mode. The approach was evaluated with various architectures on benchmark datasets and achieved better results than state-of-the-art quantization approaches. On CIFAR-10, it achieved an error rate of only 5.71%, and on CIFAR-100, it achieved an error rate of 27.65%.


## Target Task

computer vision

## Content

<Abstract: >We propose SYMOG (symmetric mixture of Gaussian modes) as a novel soft quantization method for decreasing the complexity of deep neural networks (DNNs) through low-bit fixed-point quantization. During training, the weight distribution changes from an unimodal Gaussian distribution to a symmetric mixture of Gaussians where each mean value belongs to a particular fixed-point mode. We evaluate our approach with different architectures on benchmark datasets and achieve excellent results, outperforming state-of-the-art quantization approaches. We achieve an error rate of only 5.71% on CIFAR-10 and 27.65% on CIFAR-100.



---

