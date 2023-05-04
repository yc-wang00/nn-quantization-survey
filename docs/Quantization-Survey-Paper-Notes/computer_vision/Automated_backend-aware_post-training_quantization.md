# Automated backend-aware post-training quantization

## Summary

Summary: The paper presents an automated post-training quantization framework called HAGO that provides a set of general quantization graph transformations to find the optimal quantization strategy while satisfying hardware constraints for any model. HAGO achieves a speedup of up to 2.48x on various hardware backends without compromising accuracy.


## Target Task

computer vision

## Content

<Abstract: >Quantization is a technique used to decrease resource requirements and improve the performance of neural network deployment. However, implementing quantized networks for different hardware backends requires specialized post-training quantization pipelines to be built for each hardware target, an engineering effort that is often too large for developers to keep up with. In this paper, an automated post-training quantization framework called HAGO is presented to tackle this problem. HAGO provides a set of general quantization graph transformations based on a user-defined hardware specification and implements a search mechanism to find the optimal quantization strategy while satisfying hardware constraints for any model. HAGO is shown to achieve speedups of 2.09x, 1.97x, and 2.48x on Intel Xeon Cascade Lake CPUs, NVIDIA Tesla T4 GPUs, ARM Cortex-A CPUs on Raspberry Pi4 relative to full precision, respectively, while maintaining the highest reported post-training quantization accuracy in each case.



---

