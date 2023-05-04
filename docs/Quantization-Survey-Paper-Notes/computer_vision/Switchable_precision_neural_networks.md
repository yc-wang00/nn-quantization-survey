# Switchable precision neural networks

## Summary

<Summary: > The paper proposes a flexible quantization strategy called Switchable Precision neural Networks (SP-Nets), which allows a shared network to operate at multiple quantization levels based on instant memory, latency, power consumption, and accuracy demands. The network can adjust its precision on the fly from BinaryConnect to Binarized Neural Network enabling dot-products using only summations or bit operations. The paper also proposes a self-distillation scheme to increase the performance of the quantized switches. The approach is tested with three different quantizers, and the performance of SP-Nets is demonstrated against independently trained quantized models for classification accuracy for Tiny ImageNet and ImageNet datasets using ResNet-18 and MobileNet architectures.


## Target Task

computer vision

## Content

<Abstract: >Instantaneous and on demand accuracy-efﬁciency trade-off has been recently explored in the context of neural networks slimming. In this paper, we propose a ﬂexible quantization strategy, termed Switchable Precision neural Networks (SP-Nets), to train a shared network capable of operating at multiple quantization levels. At runtime, the network can adjust its precision on the ﬂy according to instant memory, latency, power consumption and accuracy demands. For example, by constraining the network weights to 1-bit with switchable precision activations, our shared network spans from BinaryConnect to Binarized Neural Network, allowing to perform dot-products using only summations or bit operations. In addition, a self-distillation scheme is proposed to increase the performance of the quantized switches. We tested our approach with three different quantizers and demonstrate the performance of SP-Nets against independently trained quantized models in classification accuracy for Tiny ImageNet and ImageNet datasets using ResNet-18 and MobileNet architectures.



---

