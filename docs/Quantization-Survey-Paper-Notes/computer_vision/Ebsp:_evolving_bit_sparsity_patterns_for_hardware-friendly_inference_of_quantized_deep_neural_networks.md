# Ebsp: evolving bit sparsity patterns for hardware-friendly inference of quantized deep neural networks

## Summary

Summary: This paper introduces EBSP, a novel technique for compressing DNN models for hardware-friendly inference on edge-computing platforms. EBSP integrates aggressive joint-way compression with hardware design by introducing bit sparsity patterns that construct both expressive and regular bit distribution in the quantized network. It overall aims to optimize the precision of operands in quantization, resulting in energy reduction and performance gain. The paper outlines the limitations of existing compression techniques and highlights how the proposal overcomes them.


## Target Task

computer vision

## Content

<Abstract:> This paper proposes a novel technique, EBSP, for the compression of DNN models, specifically for hardware-friendly inference on edge-computing platforms. It aims to integrate aggressive joint-way compression with hardware design by introducing bit sparsity patterns that construct both highly expressive and inherently regular bit distribution in the quantized network. The paper further incorporates sparsity constraint in training to evolve inherently bit distributions to the sparsity pattern. Using EBSP, a quantized network constrained by bit sparsity pattern can be processed using LUTs with the fewest entries instead of multipliers in minimally modified computational hardware, resulting in energy reduction and performance gain. The paper outlines the challenges with existing compression techniques and proposes a new angle of bit-level sparsity to optimize precision of operands in quantization. The contributions of the paper are outlined in detail.



---

