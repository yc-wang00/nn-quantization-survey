# Fully quantized network for object detection

## Summary

Summary: This paper addresses the challenge of maintaining network accuracy while using low bitwidth arithmetic for efficient neural network inference. The proposed techniques successfully overcome the instability during the fine-tuning stage of the quantization process and produce fully quantized 4-bit detectors based on RetinaNet and Faster R-CNN. The results show that the proposed methods achieve state-of-the-art performance for quantized detectors with more than 3.8× less loss compared to existing methods.


## Target Task

computer vision

## Content

<Abstract:> Efficient neural network inference is important in many practical domains, such as deployment in mobile settings. A method for increasing inference efficiency is to use low bitwidth arithmetic which can be accelerated using dedicated hardware. However, effective quantization schemes while maintaining network accuracy is still challenging. This paper addresses the instability during the fine-tuning stage of the quantization process and proposes techniques to overcome these instabilities. The proposed techniques are applied to produce fully quantized 4-bit detectors based on RetinaNet and Faster R-CNN, and they show that these achieve state-of-the-art performance for quantized detectors. The mAP loss due to quantization using these methods is more than 3.8× less than the loss from existing methods.



---

