# A tinyml platform for on-device continual learning with quantized latent replays

## Summary

Summary: The paper introduces a hardware/software platform for end-to-end Continual Learning based on a 10-core FP32-enabled parallel ultra-low-power (PULP) processor. They leverage the quantization of the frozen stage of the model and Latent Replays (LRs) to reduce their memory cost with minimal accuracy impact. They introduce optimized primitives for forward and backward propagation and data tiling strategies to fully exploit its memory hierarchy. The results demonstrate that by combining these techniques, continual learning can be achieved using less than 64MB of memory - an amount compatible with embedding in TinyML devices.


## Target Task

Target: Embedded Systems/ TinyML.

## Content

<Abstract:>
In this research paper, the authors introduce a hardware/software platform for end-to-end Continual Learning (CL). The platform is designed based on a 10-core FP32-enabled parallel ultra-low-power (PULP) processor. The authors leverage the quantization of the frozen stage of the model and Latent Replays (LRs) to reduce their memory cost with minimal impact on accuracy. The 8-bit compression of the LR memory proves to be almost lossless compared to the full-precision baseline implementation, but requires 4 times less memory, while 7-bit can also be used with additional minimal accuracy degradation. They also introduce optimized primitives for forward and backward propagation on the PULP processor, together with data tiling strategies to fully exploit its memory hierarchy while maximizing efficiency. The results demonstrate that by combining these techniques, continual learning can be achieved in practice using less than 64MB of memory - an amount compatible with embedding in TinyML devices.



---

