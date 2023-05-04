# Automated flow for compressing convolution neural networks for efficient edge-computation with FPGA

## Summary

<Summary: > The paper discusses the quantization of CNN models to lower bit-width parameters and activations for more efficient performance on low-power and low-cost devices. The authors present an automatic flow, from trained TensorFlow models to FPGA system on chip implementation of binarized CNN, and demonstrate its effectiveness through implementation of binarized "YOLOV2" on a low-cost, low-power FPGA device with significant performance benefits in terms of model size and inference speed on FPGA as compared to CPU and mobile CPU platforms.


## Target Task

computer vision

## Content

<Abstract: > Deep convolutional neural networks (CNN) based solutions are the current state-of-the-art for computer vision tasks. Due to the large size of these models, they are typically run on clusters of CPUs or GPUs. However, power requirements and cost budgets can be a major hindrance in adoption of CNN for IoT applications. Recent research highlights that CNN contain significant redundancy in their structure and can be quantized to lower bit-width parameters and activations, while maintaining acceptable accuracy. Low bit-width and especially single bit-width (binary) CNN are particularly suitable for mobile applications based on FPGA implementation, due to the bitwise logic operations involved in binarized CNN. Moreover, the transition to lower bit-widths opens new avenues for performance optimizations and model improvement. In this paper, we present an automatic flow from trained TensorFlow models to FPGA system on chip implementation of binarized CNN. This flow involves quantization of model parameters and activations, generation of network and model in embedded-C, followed by automatic generation of the FPGA accelerator for binary convolutions. The automated flow is demonstrated through implementation of binarized "YOLOV2" on the low cost, low power Cyclone-V FPGA device. Experiments on object detection using binarized YOLOV2 demonstrate significant performance benefit in terms of model size and inference speed on FPGA as compared to CPU and mobile CPU platforms. Furthermore, the entire automated flow from trained models to FPGA synthesis can be completed within one hour.



---

