# Edge inference with fully differentiable quantized mixed precision neural networks

## Summary

Summary: This paper proposes a new approach for mixed precision CNNs' quantization targeting edge-computing, employing hardware-aware heterogeneous differentiable quantization, targeted gradient modification, and a multi-phase learning schedule. The proposed method establishes a new pareto frontier in model accuracy and memory footprint, delivering best-in-class accuracy below 4.3 MB of weights and activations, demonstrating the effectiveness of these techniques on the ImageNet dataset across a range of models, including EfficientNet-Lite0 and MobileNetV2 models.


## Target Task

computer vision

## Content

<Abstract: >The large computing and memory cost of deep neural networks (DNNs) often precludes their use in resource-constrained devices. Quantizing the parameters and operations to lower bit-precision offers substantial memory and energy savings for neural network inference, facilitating the use of DNNs on edge computing platforms. Recent efforts at quantizing DNNs have employed a range of techniques encompassing progressive quantization, step-size adaptation, and gradient scaling. This paper proposes a new quantization approach for mixed precision convolutional neural networks (CNNs) targeting edge-computing. Our method establishes a new pareto frontier in model accuracy and memory footprint demonstrating a range of quantized models, delivering best-in-class accuracy below 4.3 MB of weights (wgts.) and activations (acts.). Our main contributions are: (i) hardware-aware heterogeneous differentiable quantization with tensor-sliced learned precision, (ii) targeted gradient modification for wgts. and acts. to mitigate quantization errors, and (iii) a multi-phase learning schedule to address instability in learning arising from updates to the learned quantizer and model parameters. We demonstrate the effectiveness of our techniques on the ImageNet dataset across a range of models including EfficientNet-Lite0 (e.g., 4.14MB of wgts. and acts. at 67.66% accuracy) and MobileNetV2 (e.g., 3.51MB wgts. and acts. at 65.39% accuracy).



---

