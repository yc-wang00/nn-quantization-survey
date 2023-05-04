# Integer-only zero-shot quantization for efficient speech recognition

## Summary

<Summary: > The paper proposes an integer-only, zero-shot quantization scheme for ASR models that achieves significant speedup and compression rate. The approach is applied to QuartzNet, Jasper, and Conformer without any access to training and/or validation data and results in a modest WER degradation of <1% with INT8 quantization.


## Target Task

speech recognition

## Content

<Abstract: >End-to-end neural network models for speech recognition tasks often perform poorly on edge hardware due to large memory and computation requirements. While quantizing model weights and/or activations to low-precision can be a promising solution, previous research lacks integer-only and zero-shot quantization methods for ASR models. In this paper, we propose an integer-only, zero-shot quantization scheme for ASR models that achieves negligible WER degradation even without any access to training and/or validation data. We apply our method to QuartzNet, Jasper, and Conformer and demonstrate significant speedup and compression rate, with a modest WER degradation of <1% with INT8 quantization.



---

