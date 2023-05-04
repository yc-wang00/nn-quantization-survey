# Simulated Quantization, Real Power Savings

## Summary

<Summary: >This paper proposes reducing power consumption in neural network inference by using consecutive 0 bits from the multipliers to simulate low bit-width quantization on higher bit-width hardware. They show that simulating 4-bit quantization on 8-bit hardware can result in up to 17% relative reduction in power consumption. The use of bit operations (BOPs) as a proxy for power efficiency is also discussed, and learning mixed-precision configurations targeting lower BOPs can achieve better trade-offs between accuracy and power efficiency.


## Target Task

computer vision

## Content

<Abstract: >Reduced precision hardware-based matrix multiplication accelerators have been widely used to reduce power consumption in neural network inference. In this paper, we show that the effect of consecutive 0 bits from the multipliers can be used to further reduce power consumption by simulating low bit-width quantization on higher bit-width hardware. We demonstrate that simulating 4-bit quantization on 8-bit hardware can result in up to 17% relative reduction in power consumption on commonly used networks. We also show that bit operations (BOPs) can be used as a proxy for power efficiency, and learning mixed-precision configurations targeting lower BOPs can achieve better trade-offs between accuracy and power efficiency.



---

