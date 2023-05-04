# 4-bit Conformer with native quantization aware training for speech recognition

## Summary

Summary: The paper proposes the use of 4-bit ASR models with native quantization aware training to achieve higher compression rates without compromising on performance. The experiments performed on state-of-the-art Conformer-based ASR models on the LibriSpeech dataset and a practical ASR system trained with large-scale datasets produced lossless models with significant size reduction.


## Target Task

speech recognition

## Content

<Abstract: >Reducing the latency and model size for live Automatic Speech Recognition (ASR) has been a significant research problem. To compress neural networks and reduce computation cost, model quantization has become an increasingly popular approach. To achieve a higher compression rate without introducing additional performance regression, in this study, we propose to develop 4-bit ASR models with native quantization aware training. We conducted two experiments on state-of-the-art Conformer-based ASR models to evaluate our proposed quantization technique. First, we explored the impact of different precisions for both weight and activation quantization on the LibriSpeech dataset and produced a lossless 4-bit Conformer model with 5.8x size reduction. Following this, we investigated and revealed the viability of 4-bit quantization on a practical ASR system that is trained with large-scale datasets and produced a lossless Conformer ASR model with mixed 4-bit and 8-bit weights that has 5x size reduction.



---

