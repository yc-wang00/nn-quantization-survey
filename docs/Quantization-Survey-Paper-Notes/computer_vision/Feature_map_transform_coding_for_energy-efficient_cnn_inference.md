# Feature map transform coding for energy-efficient cnn inference

## Summary

<Summary: > The paper proposes a lossy transform coding approach to reduce the memory bandwidth requirements of Convolutional neural networks (CNN), which often dominate the energy footprint on modern hardware. This approach compresses feature maps, which are highly correlated, with variable length coding without requiring fine-tuning the network weights. The proposed method outperforms previous approaches in terms of the number of bits per value with minor accuracy degradation on ResNet-34 and MobileNetV2. The reduction of 40% in the memory energy footprint is achieved in FPGA implementation of ResNet-18 with negligible impact on accuracy.


## Target Task

computer vision

## Content

<Abstract: >Convolutional neural networks (CNNs) achieve state-of-the-art accuracy in a variety of tasks in computer vision and beyond. One of the major obstacles hindering the ubiquitous use of CNNs for inference on low-power edge devices is their high computational complexity and memory bandwidth requirements. The latter often dominates the energy footprint on modern hardware. In this paper, we introduce a lossy transform coding approach, inspired by image and video compression, designed to reduce the memory bandwidth due to the storage of intermediate activation calculation results. Our method does not require fine-tuning the network weights and halves the data transfer volumes to the main memory by compressing feature maps, which are highly correlated, with variable length coding. Our method outperforms previous approaches in the term of the number of bits per value with minor accuracy degradation on ResNet-34 and MobileNetV2. We analyze the performance of our approach on a variety of CNN architectures and demonstrate that FPGA implementation of ResNet-18 with our approach results in a reduction of around 40% in the memory energy footprint, compared to quantized network, with negligible impact on accuracy. When allowing accuracy degradation of up to 2%, the reduction of 60% is achieved. A reference implementation accompanies the paper.



---

