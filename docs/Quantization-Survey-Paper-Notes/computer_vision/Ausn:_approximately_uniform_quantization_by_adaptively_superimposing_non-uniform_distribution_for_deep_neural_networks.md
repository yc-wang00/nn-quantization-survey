# Ausn: approximately uniform quantization by adaptively superimposing non-uniform distribution for deep neural networks

## Summary

<Summary: > The paper proposes an advanced quantization method called AUSN that uses a decoder-free coding scheme, superposition quantization algorithm, and rounding scheme to harness the bit-width usage, adapt the coding scheme to diverse DNN layers and tasks, and prevent bit-width overflow and re-quantization errors. It is effective for different DNN models, as supported by theoretical analysis and accuracy assessment. FPGA synthesis results demonstrate a 2x reduction in energy consumption and a 2x-4x reduction in hardware resources.


## Target Task

computer vision

## Content

<Abstract: >Quantization of deep neural networks is essential for reducing the complexity of DNN inference in edge applications. However, existing uniform and non-uniform quantization methods inherently have a conflict between representing range and resolving resolution, resulting in either underutilized bit-width or significant accuracy drop. This paper aims to propose a novel quantization method called AUSN that consists of a decoder-free coding scheme, a superposition quantization algorithm, and a rounding scheme. AUSN successfully exploits the bit-width to its extreme, adapts the coding scheme to different DNN layers, models, and tasks without extra hardware design effort, and eliminates bit-width overflow and re-quantization issues. The effectiveness and generalization of AUSN are supported by theoretical analysis and accuracy evaluation on various DNN models of different tasks. Moreover, the synthesis results on FPGA show a reduction of 2x in energy consumption and a 2x to 4x reduction in hardware resources.



---

