# Pact: Parameterized clipping activation for quantized neural networks

## Summary

Summary: The paper presents a novel activation quantization scheme called PACT, which optimizes the activation clipping parameter alpha during training to find the right quantization scale. This technique enables quantizing activations to arbitrary bit precisions while still achieving better accuracy than existing quantization schemes. The paper demonstrates that both weights and activations can be quantized to 4-bits of precision, achieving accuracy comparable to full precision networks across multiple models and datasets. The proposed reduced-precision computational units can also enable significant inferencing performance improvement due to a reduction in accelerator compute engine size and on-chip memory usage.


## Target Task

computer vision

## Content

<Abstract: > 
This paper proposes a novel quantization scheme for activations during training, called PArameterized Clipping acTivation (PACT). PACT enables neural networks to work well with ultra low precision weights and activations without any significant accuracy degradation. The activation clipping parameter alpha is optimized during training to find the right quantization scale. This technique allows quantizing activations to arbitrary bit precisions, while achieving much better accuracy relative to published state-of-the-art quantization schemes. The paper demonstrates that both weights and activations can be quantized to 4-bits of precision while still achieving accuracy comparable to full precision networks across a range of popular models and datasets. The reduced-precision computational units can also enable a super-linear improvement in inferencing performance due to a significant reduction in the area of accelerator compute engines coupled with the ability to retain the quantized model and activation data in on-chip memories.



---

