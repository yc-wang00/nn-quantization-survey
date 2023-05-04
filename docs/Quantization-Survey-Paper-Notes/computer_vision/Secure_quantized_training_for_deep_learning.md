# Secure quantized training for deep learning

## Summary

<Summary: > A secure multi-party computation (MPC) training of neural networks is implemented using quantization. The article reports the first successful MPC trained MNIST classifier to reach an accuracy of 99.2% in 3.5 hours with a 0.2% accuracy difference from the same network trained via plaintext computation. Additionally, the article presents novel protocols for exponentiation and inverse square root and tests the implementation in various MPC security models for up to ten parties, both with honest and dishonest majority as well as semi-honest and malicious security.


## Target Task

computer vision

## Content

<Abstract: >We implement training of neural networks in secure multi-party computation (MPC) using quantization commonly used in said setting. We are the first to present an MNIST classifier purely trained in MPC that comes within 0.2 percent of the accuracy of the same convolutional neural network trained via plaintext computation. More concretely, we have trained a network with two convolutional and two dense layers to 99.2% accuracy in 3.5 hours (under one hour for 99% accuracy). We have also implemented AlexNet for CIFAR-10, which converges in a few hours. We develop novel protocols for exponentiation and inverse square root. Finally, we present experiments in a range of MPC security models for up to ten parties, both with honest and dishonest majority as well as semi-honest and malicious security.



---

