# On periodic functions as regularizers for quantization of neural networks

## Summary

<Summary: >The paper proposes a method for quantizing neural network models by adding periodic functions as regularizers during training. The resulting quantized models maintain their accuracy and exhibit the same accuracy as the original ones on CIFAR-10 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract: > Deep learning models require a significant amount of resources during training and inference, particularly when smaller devices like smartphones or embedded systems are used. Due to the limitations of these devices' size, temperature, and power budget, quantizing the model parameters into discrete integer numbers is a common technique to decrease their storage and compute requirements. This paper proposes an algorithm based on periodic functions like continuous trigonometric sine or cosine, and non-continuous hat functions as regularizers, to perform quantization of neural network models. By adding the sum over the model parameters during training, the weights are pushed into discrete points, which can be encoded as integers. The frequency and amplitude hyper-parameters of these functions can be adjusted, and the resulting quantized models maintain their accuracy. The experimentation showed that models quantized using this technique exhibit the same accuracy as the original ones on CIFAR-10 and ImageNet datasets.



---

