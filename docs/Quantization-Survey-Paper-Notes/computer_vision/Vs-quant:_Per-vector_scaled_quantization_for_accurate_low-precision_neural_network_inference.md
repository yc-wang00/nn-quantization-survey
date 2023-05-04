# Vs-quant: Per-vector scaled quantization for accurate low-precision neural network inference

## Summary

Summary: The paper proposes a new method of per-vector scaled quantization to accelerate deep neural networks through quantization without resulting in accuracy degradation. The method uses a separate scale factor for each small vector with low-bitwidth integers and achieves better inference accuracy at low precision compared to conventional scaling techniques for popular neural networks. The method resulted in energy and area saving over an 8-bit baseline and maintained over 75% accuracy for ResNet50 on ImageNet and achieved near-full-precision accuracy for both BERT-base and BERT-large on SQuAD without requiring retraining.


## Target Task

computer vision

## Content

<Abstract: >Quantization is a way of accelerating deep neural networks that reduces memory footprint and exploits low-cost integer math hardware. However, excessive quantization can cause accuracy degradation. To address this, a new method called per-vector scaled quantization is proposed, which uses a separate scale factor for each small vector of (16-64) elements within a single dimension of a tensor. To achieve an efficient hardware implementation, the per-vector scale factors can be implemented with low-bitwidth integers when calibrated using a two-level quantization scheme. The method achieves better inference accuracy at low precision compared to conventional scaling techniques for popular neural networks without requiring retraining. It also resulted in energy saving and area saving over an 8-bit baseline, while maintaining over 75% accuracy for ResNet50 on ImageNet, and achieving near-full-precision accuracy for both BERT-base and BERT-large on SQuAD.



---

