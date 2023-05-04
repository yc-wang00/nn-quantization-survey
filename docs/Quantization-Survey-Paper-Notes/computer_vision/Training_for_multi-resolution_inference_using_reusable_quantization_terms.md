# Training for multi-resolution inference using reusable quantization terms

## Summary

<Summary: > The paper proposes a training approach that supports multi-resolution inference by reusing quantization terms and introduces a multi-resolution Multiply-Accumulator (mMAC) design. The approach enables the creation of Deep Neural Network models that can support up to 10 resolutions with a moderate performance reduction, allowing for a broader range of choices in trading off cost, efficiency, and latency across different computational budgets.


## Target Task

computer vision

## Content

<Abstract:> Low-resolution uniform quantization, particularly 4-bit bitwidth, has significantly improved the efficiency of Deep Neural Network (DNN) inference. However, it presents a trade-off between performance and hardware cost. To address this concern, the authors present a novel training approach that supports multi-resolution inference by reusing quantization terms. They also introduce a multi-resolution Multiplier-Accumulator (mMAC) design that allows a hardware platform to support multiple resolutions at runtime, which takes fewer cycles to multiply lower-resolution numbers and more cycles to multiply higher-resolution numbers. The authors evaluate their approach on multiple applications and show that models resulting from their approach can support up to 10 resolutions with only a moderate performance reduction compared to individually trained models. They also compare their multi-resolution mMAC design with other conventional MAC designs and show that it broadens the choices for trading off cost, efficiency, and latency across a range of computational budgets.



---

