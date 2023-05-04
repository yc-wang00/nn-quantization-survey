# Do All MobileNets Quantize Poorly? Gaining Insights into the Effect of Quantization on Depthwise Separable Convolutional Networks Through the Eyes of Multi-scale …

## Summary

Summary: The paper focuses on the quantization issue in MobileNets, the family of deep convolutional neural networks suitable for mobiles. While existing studies have introduced quantization-aware training and other methods, there is still limited understanding of why MobileNets quantize poorly compared to other CNN architectures. To gain deeper insights into this phenomenon, the authors investigate the impact of quantization on the weight and activation distributional dynamics of MobileNet-V1, reveal significant dynamic range fluctuations and a "distributional mismatch" between channel-wise and layer-wise distributions in DWSCNNs, and suggest innovative strategies for reducing such changes and improving post-training quantization for mobile.


## Target Task

computer vision

## Content

<Abstract: >As the “Mobile AI” revolution continues to grow, so does the need to understand the behaviour of edge-deployed deep neural networks. In particular, MobileNets [ 9,22] are the go-to family of deep convolutional neural networks (CNN) for mobile. However, they often have significant accuracy degradation under post-training quantization. While studies have introduced quantization-aware training and other methods to tackle this challenge, there is limited understanding into why MobileNets (and potentially depthwise-separable CNNs (DWSCNN) in general) quantize so poorly compared to other CNN architectures. Motivated to gain deeper insights into this phenomenon, we take a different strategy and study the multi-scale distributional dynamics of MobileNet-V1, a set of smaller DWSCNNs, and regular CNNs. Speciﬁcally, we investigate the impact of quantization on the weight and activation distributional dynamics as information propagates from layer to layer, as well as overall changes in distributional dynamics at the network level. This ﬁne-grained analysis revealed significant dynamic range ﬂuctuations and a “distributional mismatch” between channelwise and layerwise distributions in DWSCNNs that lead to increasing quantized degradation and distributional shift during information propagation. Furthermore, analysis of the activation quantization errors show that there is greater quantization error accumulation in DWSCNN compared to regular CNNs. The hope is that such insights can lead to innovative strategies for reducing such distributional dynamics changes and improve post-training quantization for mobile.



---

