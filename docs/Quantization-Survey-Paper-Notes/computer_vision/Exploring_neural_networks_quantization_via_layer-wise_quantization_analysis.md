# Exploring neural networks quantization via layer-wise quantization analysis

## Summary

Summary: This paper presents an analytic framework for quantization which breaks down overall degradation to its per-layer contributions, revealing the intrinsic and extrinsic factors that determine a layer's contribution to degradation. Layer-wise analysis allows for a more nuanced examination of how quantization affects the network, and identifies local fail-cases not reflected when inspecting overall performance. The authors demonstrate how the approach can be used to design better performing quantization schemes, using an example of state-of-the-art post-training quantization methods performing poorly on a single layer of ResNext26.


## Target Task

computer vision

## Content

<Abstract: >Quantization is a crucial step in deploying deep learning models, but fails cases resulting in excessive degradation are not addressed in current literature. In this paper, the authors present an analytic framework that breaks down overall degradation to its per-layer contributions. They observe that a layer's contribution is determined by intrinsic (local) factors, such as the distribution of the layer's weights and activations, and extrinsic (global) factors, such as interaction with the rest of the layers. Layer-wise analysis of existing quantization schemes reveals local fail-cases not reflected when inspecting their overall performance. The authors also present an example of ResNext26 on which state-of-the-art post-training quantization methods perform poorly, and show that almost all of the degradation stems from a single layer. Layer-wise analysis allows for a more nuanced examination of how quantization affects the network, enabling the design of better performing schemes.



---

