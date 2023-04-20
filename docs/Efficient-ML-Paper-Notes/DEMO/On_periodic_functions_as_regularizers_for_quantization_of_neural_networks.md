# On periodic functions as regularizers for quantization of neural networks

## Summary

<Summary: >The paper proposes an unconventional method for quantization of model parameters based on periodic functions such as continuous sine or cosine and non-continuous hat functions. The approach applies these functions in a component-wise manner and adds the sum over the model parameters as a regularizer to the model loss during training. This pushes the weights into discrete points that can be encoded as integers and shows that the quantized models exhibit similar accuracy as the original ones on CIFAR-10 and ImageNet datasets.


## Target Task

Target: Computer Vision

## Content

<Abstract: >Deep learning models have been successfully used in computer vision and many other ﬁelds. We propose an unorthodox algorithm for performing quantization of the model parameters. In contrast with popular quantization schemes based on thresholds, we use a novel technique based on periodic functions, such as continuous trigonometric sine or cosine as well as non-continuous hat functions. We apply these functions component-wise and add the sum over the model parameters as a regularizer to the model loss during training. The frequency and amplitude hyper-parameters of these functions can be adjusted during training. The regularization pushes the weights into discrete points that can be encoded as integers. We show that using this technique the resulting quantized models exhibit the same accuracy as the original ones on CIFAR-10 and ImageNet datasets.



---

