# Hawq: Hessian aware quantization of neural networks with mixed-precision

## Summary

Summary: The paper introduces Hessian AWare Quantization (HAWQ), which is a second-order quantization method that provides a systematic approach to determine the relative quantization precision of each layer based on the Hessian spectrum. The results demonstrate that HAWQ achieves similar or better accuracy with 8x activation compression ratio than recently proposed methods on ResNet20 and up to 1% higher accuracy with up to 14% smaller models on ResNet50 and Inception-V3. In addition, HAWQ can quantize SqueezeNext to just 1MB model size while maintaining above 68% top1 accuracy on ImageNet.


## Target Task

computer vision

## Content

<Abstract: > Model size and inference speed/power are major challenges in the deployment of neural networks. Uniformly quantizing a model to ultra-low precision leads to significant accuracy degradation. A promising solution is mixed-precision quantization, but there is no systematic way to determine the precision of different layers. Hessian AWare Quantization (HAWQ) is introduced as a second-order quantization method that provides a deterministic fine-tuning order for quantizing layers. HAWQ allows for the automatic selection of the relative quantization precision of each layer, based on the layer’s Hessian spectrum. Results show that HAWQ achieves similar/better accuracy with 8x activation compression ratio on ResNet20 and up to 1% higher accuracy with up to 14% smaller models on ResNet50 and Inception-V3, compared to recently proposed methods. Furthermore, HAWQ can quantize SqueezeNext to just 1MB model size while achieving above 68% top1 accuracy on ImageNet.



---

