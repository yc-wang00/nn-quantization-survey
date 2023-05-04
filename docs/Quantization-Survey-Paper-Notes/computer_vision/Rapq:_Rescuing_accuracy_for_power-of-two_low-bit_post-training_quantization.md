# Rapq: Rescuing accuracy for power-of-two low-bit post-training quantization

## Summary

<Summary: >Authors propose a Power-of-Two low-bit post-training quantization method, called RAPQ, which dynamically adjusts the Power-of-Two scales of the whole network instead of statically determining them layer by layer. The proposed method outperforms SOTA PTQ methods with nearly the same accuracy, reaching an accuracy of 65% and 48% on ResNet-18 and MobileNetV2 respectively with weight INT2 activation INT4 on ImageNet.


## Target Task

computer vision

## Content

<Abstract: >We introduce a Power-of-Two low-bit post-training quantization(PTQ) method for deep neural network that meets hardware requirements and does not call for long-time retraining. We propose a novel Power-of-Two PTQ framework, dubbed RAPQ, which dynamically adjusts the Power-of-Two scales of the whole network instead of statically determining them layer by layer. Extensive experiments on ImageNet prove the excellent performance of our proposed method. Without bells and whistles, RAPQ can reach accuracy of 65% and 48% on ResNet-18 and MobileNetV2 respectively with weight INT2 activation INT4. We are the first to propose the more constrained but hardware-friendly Power-of-Two quantization scheme for low-bit PTQ specially and prove that it can achieve nearly the same accuracy as SOTA PTQ method.



---

