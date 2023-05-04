# Loss aware post-training quantization

## Summary

<Summary: > This paper analyzes the effects of quantization on loss landscape structure and demonstrates that quantizing layer parameters jointly can improve accuracy in post-training quantization methods for deep neural networks on resource-constrained devices. Results suggest that mild quantization does not greatly impact accuracy, but more aggressive quantization results in a non-separable loss landscape with steep curvature. The reference implementation is provided in the paper repository.


## Target Task

computer vision

## Content

<Abstract: > Neural network quantization enables the deployment of large models on resource-constrained devices. Current post-training quantization methods fall short in terms of accuracy for INT4 (or lower) but provide reasonable accuracy for INT8 (or above). In this work, we study the effect of quantization on the structure of the loss landscape. Additionally, we show that the structure is flat and separable for mild quantization, enabling straightforward post-training quantization methods to achieve good results. We show that with more aggressive quantization, the loss landscape becomes highly non-separable with steep curvature, making the selection of quantization parameters more challenging. Armed with this understanding, we design a method that quantizes the layer parameters jointly, enabling significant accuracy improvement over current post-training quantization methods. Reference implementation is available at the paper repository. Keywords: Deep Neural Networks, Quantization, Post-training Quantization, Compression.



---

