# GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers

## Summary

<Summary: > The paper presents GPTQ - a new one-shot weight quantization method based on approximate second-order information for Generative Pre-trained Transformer models (GPT or OPT) with 175 billion parameters. The proposed method can reduce the bitwidth down to 3 or 4 bits per weight in just 4 GPU hours with minimal accuracy degradation compared to the uncompressed baseline. GPTQ helps to improve the compression gains in comparison to previous quantization methods and enables the execution of a 175 billion-parameter model inside a single GPU for generative inference.


## Target Task

computer vision

## Content

<Abstract: >Generative Pre-trained Transformer models, known as GPT or OPT, have high computational and storage costs due to their massive size, limiting their usability. In this paper, we propose GPTQ, a new one-shot weight quantization method based on approximate second-order information, that is both highly-accurate and highly-efficient. GPTQ can quantize GPT models with 175 billion parameters in approximately four GPU hours, reducing the bitwidth down to 3 or 4 bits per weight, with negligible accuracy degradation relative to the uncompressed baseline. Our method more than doubles the compression gains relative to previously-proposed one-shot quantization methods, preserving accuracy, allowing us for the first time to execute a 175 billion-parameter model inside a single GPU for generative inference.



---

