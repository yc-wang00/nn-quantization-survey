# EasyQuant: Post-training quantization via scale optimization

## Summary

<Summary: > The paper presents a post-training quantization method called EasyQuant which optimizes scales of weights and activations for all layers to achieve high quantization precision, and then reduces the bit width for both weights and activations to INT7. INT16 intermediate storage and integer Winograd convolution implementation are also used to accelerate inference. Experimental results show that EQ outperforms TensorRT and can achieve near INT8 accuracy in 7 bits width post-training. The method can be used for deployment on computation-constrained devices without suffering from the cumbersome training process or accuracy drop.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors present a post-training quantization method called EasyQuant (EQ) that optimizes scales of weights and activations for all layers, targets convolutional outputs to obtain high quantization precision, and then lowers down bit width to INT7 for both weights and activations. They also adopt INT16 intermediate storage and integer Winograd convolution implementation to accelerate inference. The experimental results show that EQ outperforms the TensorRT method and can achieve near INT8 accuracy in 7 bits width post-training. The authors argue that this method can be used for deployment on computation-constrained devices without suffering from the cumbersome training process of training-based methods or accuracy drop in post-training quantization.



---

