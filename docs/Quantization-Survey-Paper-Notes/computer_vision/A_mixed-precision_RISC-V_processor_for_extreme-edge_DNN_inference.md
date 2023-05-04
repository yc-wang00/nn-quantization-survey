# A mixed-precision RISC-V processor for extreme-edge DNN inference

## Summary

<Summary: >The paper proposes a novel RISC-V ISA core MPIC based on the open-source RI5CY core that enables full support for mixed-precision Quantized Neural Network inference. The approach uses status-based SIMD instructions to dynamically set the precision of each operand in a core status register. The results show the MPIC improves both performance and energy efficiency when compared to software-based mixed-precision on RI5CY, and with respect to commercially available Cortex-M4 and M7 microcontrollers, it delivers better performance and higher efficiency.


## Target Task

computer vision

## Content

<Abstract: >Low bit-width Quantized Neural Networks (QNNs)
enable deployment of complex machine learning models on
constrained devices such as microcontrollers (MCUs) by reducing
their memory footprint. Fine-grained asymmetric quantization
(i.e., different bit-widths assigned to weights and activations on
a tensor-by-tensor basis) is a particularly interesting scheme
to maximize accuracy under a tight memory constraint [1].
However, the lack of sub-byte instruction set architecture (ISA)
support in SoA microprocessors makes it hard to fully exploit this
extreme quantization paradigm in embedded MCUs. Support for
sub-byte and asymmetric QNNs would require many precision
formats and an exorbitant amount of opcode space. In this work,
we attack this problem with status-based SIMD instructions:
rather than encoding precision explicitly, each operand’s pre-
cision is set dynamically in a core status register. We propose
a novel RISC-V ISA core MPIC (Mixed Precision Inference
Core) based on the open-source RI5CY core. Our approach
enables full support for mixed-precision QNN inference with
different combinations of operands at 16-, 8-, 4- and 2-bit
precision, without adding any extra opcode or increasing the
complexity of the decode stage. Our results show that MPIC
improves both performance and energy efﬁciency by a factor of
1.1–4.9 when compared to software-based mixed-precision on
RI5CY; with respect to commercially available Cortex-M4 and
M7 microcontrollers, it delivers 3.6–11.7 better performance
and 41–155 higher efﬁciency.



---

