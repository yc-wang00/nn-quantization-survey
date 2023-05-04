# [PDF][PDF] Trace weighted hessian-aware quantization

## Summary

<Summary: >This paper introduces a new method called trace-weighted Hessian-aware quantization to reduce memory and power requirements for neural networks used in mobile systems. The method uses the trace of the Hessian to avoid significant accuracy degradation caused by directly quantizing to ultra-low precision. Theoretical results provided show that the sensitivity of different layers to quantization can be determined using the trace of the Hessian, and this information is used for Hessian-aware fine-tuning. Experiments conducted on Inception-V3 and ResNet50 models trained on ImageNet dataset show that this approach outperforms expensive AutoML search methods and holds state-of-the-art results for quantized models.


## Target Task

computer vision

## Content

<Abstract: >Quantization is a promising approach to reduce the memory footprint and power consumption of neural networks deployed on mobile systems with limited resources. However, directly quantizing a model to ultra-low precision can cause significant accuracy degradation. In this paper, we introduce a new second-order-based method called trace-weighted Hessian-aware quantization, which does not require any expensive search methods. We provide theoretical results that show the trace of the Hessian can be used to determine the sensitivity of different layers to quantization, and we use this information to perform Hessian-aware fine-tuning. We test our approach on Inception-V3 and ResNet50 models trained on the ImageNet dataset and show that it exceeds industry-scale results achieved with expensive AutoML search methods. Both results are state-of-the-art for quantized models.



---

