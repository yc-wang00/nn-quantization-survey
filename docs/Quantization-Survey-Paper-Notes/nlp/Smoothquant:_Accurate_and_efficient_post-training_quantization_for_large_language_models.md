# Smoothquant: Accurate and efficient post-training quantization for large language models

## Summary

<Summary: >The paper proposes SmoothQuant, a post-training quantization (PTQ) solution for large language models (LLMs) that enables 8-bit weight, 8-bit activation (W8A8) quantization. The proposed solution is training-free, accuracy-preserving, and applicable to LLMs such as OPT-175B, BLOOM-176B, GLM-130B, and MT-NLG 530B. SmoothQuant achieves better hardware efficiency than existing techniques, resulting in up to 1.56x speedup and 2x memory reduction for LLMs with negligible loss in accuracy. The paper provides a turnkey solution that reduces hardware costs and democratizes LLMs.


## Target Task

nlp

## Content

<Abstract: >Large language models (LLMs) show excellent performance but are compute- and memory-intensive. We propose SmoothQuant, a training-free, accuracy-preserving, and general-purpose post-training quantization (PTQ) solution to enable 8-bit weight, 8-bit activation (W8A8) quantization for LLMs. SmoothQuant enables an INT8 quantization of both weights and activations for all the matrix multiplications in LLMs, including OPT-175B, BLOOM-176B, GLM-130B, and MT-NLG 530B. SmoothQuant has better hardware efficiency than existing techniques. We demonstrate up to 1.56x speedup and 2x memory reduction for LLMs with negligible loss in accuracy. Our work offers a turnkey solution that reduces hardware costs and democratizes LLMs.



---

