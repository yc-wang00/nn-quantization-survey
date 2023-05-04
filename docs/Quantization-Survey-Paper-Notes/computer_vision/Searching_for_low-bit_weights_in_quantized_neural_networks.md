# Searching for low-bit weights in quantized neural networks

## Summary

<Summary: >This paper presents a novel method for searching low-bit weights in quantized neural networks using a differential method to accurately search the discrete weights in an arbitrary quantized neural network. The proposed method represents each weight as a probability distribution optimized during training, resulting in better performance than state-of-the-art methods. The PyTorch code and MindSpore code are available online.


## Target Task

computer vision

## Content

<Abstract: >Quantized neural networks with low-bit weights and activations are attractive for developing AI accelerators. However, the quantization functions used in most conventional quantization methods are non-differentiable, which increases the optimization difficulty of quantized networks. This paper presents a novel method of searching for low-bit weights in quantized neural networks by regarding the discrete weights in an arbitrary quantized neural network as searchable variables and utilizing a differential method to search them accurately. Each weight is represented as a probability distribution over the discrete value set, and the probabilities are optimized during training. The proposed method is demonstrated to produce quantized neural networks with higher performance than state-of-the-art methods on both image classification and super-resolution tasks. The PyTorch code and MindSpore code will be made available at https://github.com/huawei-noah/Binary-Neural-Networks/tree/main/SLB and https://www.mindspore.cn/resources/hub, respectively.



---

