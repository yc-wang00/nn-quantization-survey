# A quantization-friendly separable convolution for mobilenets

## Summary

Summary: The paper explains the importance of making inference computations efficient for deploying deep learning on mobile/IoT devices. Quantization is an effective approach to achieve this offloading. However, existing network designs are not always quantization-friendly. The paper proposes a quantization-friendly separable convolution architecture for the popular lightweight MobileNetV1 model, to reduce the accuracy gap between quantized and float point models. The proposed modified MobileNetV1 model achieves an 8-bit inference top-1 accuracy of 68.03% on ImageNet2012 dataset, almost closing the gap to the float pipeline.


## Target Task

computer vision

## Content

<Abstract: >As deep learning (DL) is being rapidly pushed to edge computing, researchers invented various ways to make inference computation more efficient on mobile/IoT devices, such as network pruning, parameter compression, and etc. Quantization, as one of the key approaches, can effectively offload GPU and make it possible to deploy DL on fixed-point pipeline. Unfortunately, not all existing networks design are friendly to quantization. For example, the popular light-weight MobileNetV1 [1], while it successfully reduces parameter size and computation latency with separable convolution, our experiment shows its quantized models have large accuracy gap against its float point models. To resolve this, we analyzed the root cause of quantization loss and proposed a quantization-friendly separable convolution architecture. By evaluating the image classification task on ImageNet2012 dataset, our modified MobileNetV1 model can archive 8-bit inference top-1 accuracy in 68.03%, almost closed the gap to the float pipeline.
Keywords: Separable Convolution, MobileNetV1, Quantization, Fixed-point Inference



---

