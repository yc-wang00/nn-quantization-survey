# Accelerating convolutional neural networks via activation map compression

## Summary

<Summary: >This paper proposes a three-stage compression and acceleration pipeline for efficient neural network use in low-powered devices. The pipeline sparsifies, quantizes, and entropy encodes activation maps of Convolutional Neural Networks. The sparsification increases inferencing acceleration and model accuracy. The quantization and entropy encoding of the activation maps lead to a higher compression over the baseline, reducing memory cost. Inception-V3 and MobileNet-V1 can be accelerated by as much as 1.6x with an increase in accuracy on the ImageNet and CIFAR-10 datasets respectively. Activation maps, quantized to 16bits, are compressed by as much as 6x with an increase in accuracy.


## Target Task

computer vision

## Content

<Abstract: >Towards the efficient use of neural networks in low-powered devices, we propose a three-stage compression and acceleration pipeline that sparsifies, quantizes, and entropy encodes activation maps of Convolutional Neural Networks. The sparsification increases the representational power of activation maps leading to both acceleration of inference and higher model accuracy, with Inception-V3 and MobileNet-V1 being able to be accelerated by as much as 1.6x with an increase in accuracy of 0.38% and 0.54% on the ImageNet and CIFAR-10 datasets respectively. The quantizing and entropy encoding of the sparser activation maps lead to a higher compression over the baseline, reducing the memory cost of the network execution. Inception-V3 and MobileNet-V1 activation maps, quantized to 16bits, are compressed by as much as 6x with an increase in accuracy of 0.36% and 0.55% respectively.



---

