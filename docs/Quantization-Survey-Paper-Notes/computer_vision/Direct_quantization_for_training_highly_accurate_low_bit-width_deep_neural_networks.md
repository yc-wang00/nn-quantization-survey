# Direct quantization for training highly accurate low bit-width deep neural networks

## Summary

<Summary: > This paper proposes two novel techniques for the training of deep convolutional neural networks with low bit-width weights and activations. The first technique enables direct updating of quantized weights to minimize the cost function using gradient descent. The second technique considers the quantization errors of individual channels to learn activation quantizers that minimize errors in most channels. These techniques achieve state-of-the-art performance on image classification tasks using AlexNet, ResNet, and MobileNetV2 architectures on CIFAR-100 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes two novel techniques to train deep convolutional neural networks with low bit-width weights and activations. The first technique proposes a novel method that enables direct updating of quantized weights with learnable quantization levels to minimize the cost function using gradient descent, to address the mismatch caused by updating only full-precision weights. The second technique proposes a method to take into account the quantization errors of individual channels to learn activation quantizers that minimize the quantization errors in the majority of channels. The proposed method achieves state-of-the-art performance on the image classification task, using AlexNet, ResNet, and MobileNetV2 architectures on CIFAR-100 and ImageNet datasets.



---

