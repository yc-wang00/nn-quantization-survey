# Mix and match: A novel fpga-centric deep neural network quantization framework

## Summary

<Summary: > This paper focuses on weight quantization as a hardware-friendly model compression approach for deep neural networks, which concentrates on different quantization schemes for different rows of the weight matrix compared to existing methods that use the same quantization scheme for all weights. The authors propose a quantization framework for FPGA devices, which improves performance better than exploiting DSPs for all multiplication operations.


## Target Task

computer vision

## Content

<Abstract: >Deep Neural Networks (DNNs) have achieved extraordinary performance in various application domains. To support diverse DNN models, efficient implementations of DNN inference on edge-computing platforms, e.g., ASICs, FPGAs, and embedded systems, are extensively investigated. This paper focuses on weight quantization, a hardware-friendly model compression approach that is complementary to weight pruning. Unlike existing methods that use the same quantization scheme for all weights, we propose the first solution that applies different quantization schemes for different rows of the weight matrix.  We evaluate our FPGA-centric quantization framework across multiple application domains. With optimal SP2/fixed-point ratios on two FPGA devices, we achieve performance improvement of 2:1 and 4:1 compared to solely exploiting DSPs for all multiplication operations.



---

