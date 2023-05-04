# Minimum energy quantized neural networks

## Summary

Summary: The paper discusses the minimum-energy optimization of Quantized Neural Networks (QNNs) that use low-precision weights and activations. Using a model for energy consumption in a generic hardware platform, the paper finds that BinaryNets or int4 implementations result in the minimum energy solution and outperform int8 networks up to 2^10 at iso-accuracy. The paper highlights the importance of explicit control over network quantization and suggests that cross-optimizing both the used algorithm and hardware architecture can enhance the performance of always-on embedded applications.


## Target Task

computer vision

## Content

<Abstract: >This work focuses on the minimum-energy optimization of Quantized Neural Networks (QNNs), which use low-precision weights and activations. The energy consumption of inference is modeled for a generic hardware platform to analyze and quantify the fundamental trade-off between the number of bits used in the QNN and energy-efficiency. The analysis shows that energy consumption varies orders of magnitude at iso-accuracy depending on the number of bits used in the QNN. The study suggests that in a typical system, BinaryNets or int4 implementations lead to the minimum energy solution, outperforming int8 networks up to 2^10 at iso-accuracy. The work contributes to explicit control over network quantization, enabling cross-optimizing both the used algorithm and the hardware architecture for always-on embedded applications.



---

