# QGAN: Quantized generative adversarial networks

## Summary

<Summary: >The paper introduces QGAN, a novel quantization method with EM algorithms, for GANs which can quantize GAN models to 1-bit or 2-bit representations with comparable quality to original models. This technique enables real-world deployment of GANs on smartphones, which was difficult previously due to the intensive memory requirements and computations of GANs.


## Target Task

computer vision

## Content

<Abstract: > The intensive computations and memory requirements of GANs make their real-world deployment on smartphones difficult. While CNNs and RNNs have been reduced in size through quantization, GANs have not been studied using this technique due to issues with the effectiveness of quantization algorithms and the instability of training GAN models. This paper introduces QGAN, a new quantization method based on EM algorithms, for GANs. Using CIFAR-10 and CelebA datasets, QGAN is able to quantize GAN models to 1-bit or 2-bit representations with results of quality comparable to original models.



---

