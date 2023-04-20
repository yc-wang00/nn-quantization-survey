# I-ViT: integer-only quantization for efficient vision transformer inference

## Summary

Summary: The authors introduce I-ViT, an integer-only quantization method for Vision Transformers (ViTs), which employs bit-shifting and dyadic arithmetic with Shiftmax and ShiftGELU to perform inference computations without floating-point arithmetic, thus reducing model complexity for deployment on edge devices. Experimental validation on benchmark models demonstrates comparable accuracy to full-precision baselines and a significantly faster inference speedup.


## Target Task

Target: Computer vision

## Content

<Abstract: >In this paper, the authors propose I-ViT, an integer-only quantization scheme for Vision Transformers (ViTs), that enables ViTs to perform the entire computational graph of inference with integer arithmetic and bit-shifting, and without any floating-point arithmetic. They achieved this by applying the proposed Shiftmax and ShiftGELU along with dyadic arithmetic to enable the quantized models to fully benefit from fast and efficient low-precision integer arithmetic units, while reducing model complexity for practical hardware deployment on resource-constrained edge devices. The authors evaluate I-ViT on various benchmark models and show that the integer-only INT8 quantization achieves comparable (or even slightly higher) accuracy to the full-precision (FP) baseline. The authors also utilized TVM for practical hardware deployment on the GPU’s integer arithmetic units, achieving a 3.72–4.11 inference speedup compared to the FP model.



---

