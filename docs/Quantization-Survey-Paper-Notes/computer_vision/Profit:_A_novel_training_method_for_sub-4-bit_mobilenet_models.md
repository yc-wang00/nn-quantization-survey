# Profit: A novel training method for sub-4-bit mobilenet models

## Summary

Summary: The paper discusses the challenge of activation instability induced by weight quantization (AIWQ) in sub-4-bit quantization of mobile networks. The authors propose a training method called PROgressive-Freezing Iterative Training (PROFIT) to alleviate the AIWQ problem. Additionally, they propose a differentiable and unified quantization method (DuQ) and a negative padding idea for asymmetric activation functions such as h-swish. The proposed methods are evaluated on MobileNet-v1, v2, and v3 on ImageNet and show comparable accuracy to full precision baseline. The proposed method outperforms the state-of-the-art method by a large margin on the 3-bit quantization of MobileNet-v3.


## Target Task

computer vision

## Content

<Abstract: >4-bit and lower precision mobile models are required due to the ever-increasing demand for better energy efficiency‌ in mobile devices. In this work, we report that the activation instability induced by weight quantization (AIWQ) is the key obstacle to sub-4-bit quantization of mobile networks. To alleviate the AIWQ problem, we propose a novel training method called PROgressive-Freezing Iterative Training (PROFIT), which attempts to freeze layers whose weights are affected by the instability problem stronger than the other layers. We also propose a differentiable and unified quantization method (DuQ) and a negative padding idea to support asymmetric activation functions such as h-swish. We evaluate the proposed methods by quantizing MobileNet-v1, v2, and v3 on ImageNet and report that 4-bit quantization offers comparable (within 1.48 % top-1 accuracy) accuracy to full precision baseline. In the ablation study of the 3-bit quantization of MobileNet-v3, our proposed method outperforms the state-of-the-art method by a large margin, 12.86 % of top-1 accuracy. The quantized model and source code is available at https://github.com/EunhyeokPark/PROFIT. Keywords: Mobile network, quantization, activation distribution, h-swish activation



---

