# Learning to quantize deep networks by optimizing quantization intervals with task loss

## Summary

Summary: The paper proposes a method for reducing the bit-widths of deep networks using a trainable quantizer that discretizes activations and weights via optimized quantization intervals. The method can maintain accuracy of the full-precision network with a bit-width as low as 4-bit, and minimize accuracy degradation with further bit-width reduction. The method also allows for the quantization of pre-trained networks on heterogeneous datasets without access to their training data. The effectiveness of the method is demonstrated on various network architectures and datasets, achieving state-of-the-art accuracy.


## Target Task

computer vision

## Content

<Abstract: 
Reducing the bit-widths of deep networks can significantly improve their efficiency in memory and computation, making them more feasible for deployment to resource-limited devices. However, doing so using standard quantization techniques results in a drastic reduction in accuracy. To address this problem, the authors propose a method for learning to quantize activations and weights, using a trainable quantizer that discretizes them via optimized quantization intervals. By parameterizing the intervals, the quantizer is able to maintain accuracy of the full-precision network with bit-width as low as 4-bit and minimize accuracy degradation with further bit-width reduction. The trainable quantizer also allows for the quantization of pre-trained networks on heterogeneous datasets without access to their training data. The authors demonstrate the effectiveness of their method on various network architectures and datasets, achieving state-of-the-art accuracy.>



---

