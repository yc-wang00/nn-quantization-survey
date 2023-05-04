# I-ViT: integer-only quantization for efficient vision transformer inference

## Summary

<Summary: > The paper proposes an integer-only quantization scheme, I-ViT, for Vision Transformers (ViTs) that approximates floating-point operations with Shiftmax and ShiftGELU methods, enabling efficient integer-only inference for ViTs. The proposed method achieves comparable or slightly higher accuracy than the full-precision baseline on benchmark models.


## Target Task

computer vision

## Content

<Abstract: > 
In this paper, the authors propose I-ViT, an integer-only quantization scheme for Vision Transformers (ViTs), to enable efficient integer-only inference. The proposed method applies the Shiftmax and ShiftGELU methods to approximate the corresponding floating-point operations, allowing ViTs to perform the entire computational graph of inference with integer arithmetic and bit-shifting, and without any floating-point arithmetic. They evaluate I-ViT on various benchmark models and the results show that integer-only INT8 quantization achieves comparable (or even slightly higher) accuracy to the full-precision (FP) baseline.



---

