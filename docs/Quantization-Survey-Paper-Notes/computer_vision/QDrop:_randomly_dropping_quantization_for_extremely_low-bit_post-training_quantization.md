# QDrop: randomly dropping quantization for extremely low-bit post-training quantization

## Summary

Summary: This paper proposes a new approach to improve the accuracy of post-training quantization (PTQ) in extremely low-bit settings by incorporating activation quantization into PTQ reconstruction. The paper establishes a theoretical framework and introduces a simple yet effective approach called QD ROP. This approach randomly drops the quantization of activations during PTQ and produces superior results in computer vision and natural language processing tasks. QD ROP achieves state-of-the-art results in PTQ and can push the limit of PTQ to 2-bit activation for the first time with an accuracy boost of up to 51.49%.


## Target Task

computer vision

## Content

<Abstract: >Recently, post-training quantization (PTQ) has driven much attention to produce efficient neural networks without long-time retraining. Despite its low cost, current PTQ works tend to fail under the extremely low-bit setting. In this study, we pioneeringly confirm that properly incorporating activation quantization into the PTQ reconstruction benefits the final accuracy. To deeply understand the inherent reason, a theoretical framework is established, indicating that the flatness of the optimized low-bit model on calibration and test data is crucial. Based on the conclusion, a simple yet effective approach dubbed as QD ROP is proposed, which randomly drops the quantization of activations during PTQ. Extensive experiments on various tasks including computer vision (image classification, object detection) and natural language processing (text classification and question answering) prove its superiority. With QD ROP, the limit of PTQ is pushed to the 2-bit activation for the first time and the accuracy boost can be up to 51.49%. Without bells and whistles, QD ROP establishes a new state of the art for PTQ.



---

