# FAT: Training neural networks for reliable inference under hardware faults

## Summary

<Summary: > The paper proposes a methodology called fault-aware training (FAT) that incorporates error modelling into neural network training to make quantized neural networks (QNNs) resilient to specific fault models on devices. The methodology is effective in improving the error tolerance of QNNs, making them more accurate and resilient, and enabling redundant systems that achieve higher worst-case accuracy at lower hardware costs.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks are being increasingly deployed on embedded systems because of their high accuracy, despite the large compute and memory requirements. To reduce the hardware cost of using these networks in safety-critical environments, researchers have been exploring domain-specific solutions. This work proposes a novel methodology, called fault-aware training (FAT), which includes error modeling during neural network training to make quantized neural networks (QNNs) resilient to specific fault models on the device. The experiments show that highly accurate convolutional neural networks (CNNs) can be trained with FAT, which exhibit much better error tolerance compared to the original. Additionally, redundant systems that are built from QNNs trained with FAT achieve higher worse-case accuracy at lower hardware costs. 



---

