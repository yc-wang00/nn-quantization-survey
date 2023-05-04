# Qusecnets: Quantization-based defense mechanism for securing deep neural network against adversarial attacks

## Summary

<Summary: > The paper proposes Constant Quantization (CQ) and Trainable Quantization (TQ), which are two quantization-based defense mechanisms to strengthen the convolutional neural networks' robustness against adversarial attacks. CQ uses a fixed number of quantization levels, while TQ's quantization levels are iteratively learned during the training phase. These techniques were applied to various adversarial attacks from the Cleverhans library, and the result showed a significant increase in classification accuracy for perturbed images generated from the MNIST and CIFAR-10 datasets on commonly used CNN.


## Target Task

computer vision

## Content

<Abstract: >Adversarial examples are a significant threat to convolutional neural networks (CNNs). In this paper, we propose two quantization-based defense mechanisms - Constant Quantization (CQ) and Trainable Quantization (TQ) - to increase CNNs' robustness against adversarial attacks. CQ quantizes input pixel intensities based on a fixed number of quantization levels, while TQ quantization levels are iteratively learned during the training phase, providing a stronger defense mechanism. We apply the proposed techniques on different state-of-the-art adversarial attacks from the open-source Cleverhans library. The experimental results demonstrate a 50%-96% and 10%-50% increase in the classification accuracy of the perturbed images generated from the MNIST and the CIFAR-10 datasets, respectively, on commonly used CNN available in Cleverhans.



---

