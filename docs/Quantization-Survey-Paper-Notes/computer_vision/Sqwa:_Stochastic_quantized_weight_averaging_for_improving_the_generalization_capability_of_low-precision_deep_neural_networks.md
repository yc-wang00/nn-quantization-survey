# Sqwa: Stochastic quantized weight averaging for improving the generalization capability of low-precision deep neural networks

## Summary

<Summary: >The paper introduces a new approach called SQWA for optimizing low-precision DNNs using model averaging to achieve good generalization capability. The approach includes floating-point model training, direct quantization of weights, capturing multiple low-precision models during retraining, averaging the captured models, and re-quantizing the averaged model and fine-tuning it. Results demonstrate state-of-the-art performance for 2-bit QDNNs on CIFAR-100 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract: >We present SQWA, a new approach to optimize low-precision DNNs using model averaging to achieve good generalization capability. It includes (1) floating-point model training, (2) direct quantization of weights, (3) capturing multiple low-precision models during retraining, (4) averaging the captured models, and (5) re-quantizing the averaged model and fine-tuning it. Visualization results show that a quantized DNN optimized with SQWA is located near the center of the flat minimum in the loss surface, and state-of-the-art results were achieved for 2-bit QDNNs on CIFAR-100 and ImageNet datasets.



---

