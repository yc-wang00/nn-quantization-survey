# Improving neural network efficiency via post-training quantization with adaptive floating-point

## Summary

<Summary: >The paper proposes a novel Adaptive Floating-Point (AFP) format for model quantization that offers a flexible configuration of exponent and mantissa segments, enabling significant model compression rates without sacrificing accuracy. Their experiments reveal that the AFP-encoded ResNet-50/MobileNet-v2 only suffers a small accuracy degradation of ~0.04/0.6% compared to its full-precision counterpart while outperforming the state-of-the-art works by 1.1% in accuracy with the same bit-width and reducing energy consumption by 11.2×, making it an impressive technique for inference. The authors also highlight that their proposed AFP format effectively eliminates the computationally intensive de-quantization step present in the dynamic quantization technique adopted by popular machine learning frameworks.


## Target Task

computer vision

## Content

<Abstract: >Model quantization has emerged as a mandatory technique for efficient inference with advanced Deep Neural Networks (DNN) by representing model parameters with fewer bits. In this work, we propose a novel Adaptive Floating-Point (AFP) as a variant of standard IEEE-754 floating-point format, with flexible configuration of exponent and mantissa segments. Leveraging the AFP for model quantization could significantly enhance the model compression rate without accuracy degradation and model re-training. We also want to highlight that our proposed AFP could effectively eliminate the computationally intensive de-quantization step existing in the dynamic quantization technique adopted by the famous machine learning frameworks. Furthermore, we develop a framework to optimize and choose the adequate AFP configuration for each layer, thus maximizing the compression efficacy. Our experiments indicate that AFP-encoded ResNet-50/MobileNet-v2 only has ~0.04/0.6% accuracy degradation w.r.t its full-precision counterpart. It outperforms the state-of-the-art works by 1.1% in accuracy using the same bit-width while reducing the energy consumption by 11.2×, which is quite impressive for inference.



---

