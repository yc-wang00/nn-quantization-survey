# FILM-QNN: Efficient FPGA acceleration of deep neural networks with intra-layer, mixed-precision quantization

## Summary

Summary: The paper proposes a framework called FILM-QNN for quantization and acceleration of multiple DNN models across different embedded FPGA devices. It includes a novel intra-layer mixed-precision quantization algorithm that assigns different precisions to filters of each layer to improve overall throughput and hardware parallelism. Optimization techniques and a resource model for the FPGA accelerator architecture are also applied. Results show that mixed-precision implementations can achieve comparable accuracy as 8-bit versions and comparable throughput as 4-bit designs.


## Target Task

computer vision

## Content

<Abstract:> With the trend of deploying DNN models on edge devices with limited resources, quantization techniques have been widely used to reduce on-chip storage and improve computation throughput. However, existing quantization work below 8-bit may lead to accuracy loss or a big gap between theoretical improvement of computation throughput and the practical inference speedup. In this work, a general framework called FILM-QNN is proposed to quantize and accelerate multiple DNN models across different embedded FPGA devices. Specifically, a novel intra-layer, mixed-precision quantization algorithm is proposed which assigns different precisions onto the filters of each layer while preserving accuracy and improving hardware parallelism. To enhance overall throughput, multiple optimization techniques for the FPGA accelerator architecture are applied, and a comprehensive resource model is developed. Experimental results of ResNet-18, ResNet-50, and MobileNet-V2 demonstrate that implementations with intra-layer, mixed-precision can achieve comparable accuracy as 8-bit versions and comparable throughput as 4-bit designs.



---

