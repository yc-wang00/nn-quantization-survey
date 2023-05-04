# Flightnns: Lightweight quantized deep neural networks for fast and accurate inference

## Summary

Summary: The paper proposes a method for selecting the "k" value of lightweight neural networks, which constrains the weights of DNNs to be a limited combination of powers of 2 and can replace the multiply-accumulate operation with a single shift operation or two shifts and an add operation. The method is differentiable and allows for per-filter optimization of the "k" value. Results from experiments show that this method, called FLightNNs, provides 2x speedup and higher computational energy efficiency compared to other methods while only causing 0.1% accuracy degradation.


## Target Task

computer vision

## Content

<Abstract: >To improve the throughput and energy efficiency of Deep Neural Networks (DNNs) on customized hardware, lightweight neural networks constrain the weights of DNNs to be a limited combination (denoted as k∈{1,2}) of powers of 2. In such networks, the multiply-accumulate operation can be replaced with a single shift operation, or two shifts and an add operation. To provide even more design flexibility, the k for each convolutional filter can be optimally chosen instead of being fixed for every filter. In this paper, we formulate the selection of k to be differentiable, and describe model training for determining k-based weights on a per-filter basis. Over 46 FPGA-design experiments involving eight configurations and four data sets reveal that lightweight neural networks with a flexible k value (dubbed FLightNNs) fully utilize the hardware resources on Field Programmable Gate Arrays (FPGAs), our experimental results show that FLightNNs can achieve 2 × speedup when compared to lightweight NNs with k= 2, with only 0.1% accuracy degradation. Compared to a 4-bit fixed-point quantization, FLightNNs achieve higher accuracy and up to 2 × inference speedup, due to their lightweight shift operations. In addition, our experiments also demonstrate that FLightNNs can achieve higher computational energy efficiency for ASIC implementation.



---

