# Efficient quantization for neural networks with binary weights and low bitwidth activations

## Summary

Summary: This paper proposes a novel quantization strategy for deep neural networks by applying distinct quantization methods to weights and activations. They introduce CReLU, an activation function, and develop a quantization strategy that approximates weights with binary values and quantizes activations using linear or logarithmic quantizer. The proposed quantized model with binary weights and ultra-low bitwidth activations surpasses previous models and achieves significant theoretical speedup with ResNet-18. CReLU is demonstrated to be effective and robust through experiments and theoretical analysis.


## Target Task

computer vision

## Content

<Abstract:>
In this paper, the authors propose a new quantization strategy for deep neural networks which involves applying different quantization methods to weights and activations, respectively. They introduce a new activation function called CReLU and develop a specific quantization strategy which involves formulating the forward and backward approximation of weights with binary values and quantizing activations to low bitwdth using linear or logarithmic quantizer. The authors show, for the first time, that their final quantized model with binary weights and ultra-low bitwidth activations outperforms the previous best models by large margins on ImageNet, as well as achieving nearly a 10:85 theoretical speedup with ResNet-18. The effectiveness and robustness of CReLU are demonstrated through ablation experiments and theoretical analysis in comparison with other activation functions.



---

