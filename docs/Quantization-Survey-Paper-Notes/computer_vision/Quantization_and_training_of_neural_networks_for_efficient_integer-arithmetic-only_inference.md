# Quantization and training of neural networks for efficient integer-arithmetic-only inference

## Summary

<Summary: > The paper proposes a training procedure designed to maintain end-to-end model accuracy while using an integer-only quantization scheme. This scheme can increase on-device inference performance significantly while running on commonly available integer-only hardware. This approach effectively improves the tradeoff between model accuracy and on-device latency, and the results are demonstrated in ImageNet classification and COCO detection on CPUs, even on run-time efficient models like MobileNets.


## Target Task

computer vision

## Content

<Abstract:> We propose a quantization scheme to allow on-device inference to be carried out using integer-only arithmetic, which can be implemented more efficiently than floating point inference on commonly available integer-only hardware. We also co-design a training procedure to preserve end-to-end model accuracy post quantization. The proposed quantization scheme improves the tradeoff between accuracy and on-device latency. The improvements are significant even on MobileNets, a model family known for run-time efficiency, and are demonstrated in ImageNet classification and COCO detection on popular CPUs.



---

