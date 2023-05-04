# Post-training quantization for neural networks with provable guarantees

## Summary

Summary: The paper presents a generalized post-training neural network quantization method, GPFQ, which replaces network weights with quantized counterparts to achieve significant reductions in computation cost, memory usage, and power consumption. The authors propose modifications to promote weight sparsity and analyze associated errors, showing that the relative square error decays linearly with the number of weights for single-layer networks. The method is evaluated on various architectures and tested on ImageNet, demonstrating minor loss in accuracy compared to unquantized models. Standard modifications, such as bias correction and mixed precision quantization, also improve accuracy.


## Target Task

computer vision

## Content

<Abstract: While neural networks have been remarkably successful in a wide array of applications, implementing them in resource-constrained hardware remains an area of intense research. By replacing the weights of a neural network with quantized (e.g., 4-bit, or binary) counterparts, massive savings in computation cost, memory, and power consumption are attained. To that end, we generalize a post-training neural-network quantization method, GPFQ, that is based on a greedy path-following mechanism. Among other things, we propose modifications to promote sparsity of the weights, and rigorously analyze the associated error. Additionally, our error analysis expands the results of previous work on GPFQ to handle general quantization alphabets, showing that for quantizing a single-layer network, the relative square error essentially decays linearly in the number of weights { i.e., level of over-parametrization. Our result holds across a range of input distributions and for both fully-connected and convolutional architectures thereby also extending previous results. To empirically evaluate the method, we quantize several common architectures with few bits per weight, and test them on ImageNet, showing only minor loss of accuracy compared to unquantized models. We also demonstrate that standard modifications, such as bias correction and mixed precision quantization, further improve accuracy.>



---

