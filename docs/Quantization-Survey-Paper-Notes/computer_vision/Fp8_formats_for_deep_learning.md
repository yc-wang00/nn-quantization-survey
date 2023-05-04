# Fp8 formats for deep learning

## Summary

<Summary: >The paper proposes a new 8-bit floating-point binary interchange format called FP8 that aims to accelerate deep learning training inference beyond the currently used 16-bit formats found in modern processors. The proposal includes two encodings - E4M3 and E5M2. The study demonstrates the efficacy of the format in various image and language tasks, including CNNs, RNNs, and Transformer-based models without changing any of the hyperparameters from the 16-bit baseline training sessions. The paper also explores the post-training quantization of language models trained using 16-bit formats that resisted fixed-point int8 quantization.


## Target Task

computer vision

## Content

<Abstract: > FP8 is a proposed 8-bit floating-point binary interchange format that aims to accelerate deep learning training inference beyond the commonly used 16-bit formats found in modern processors. The proposal includes two encodings: E4M3 and E5M2. E4M3 extends dynamic range by not representing infinities and having only one mantissa bit-pattern for NaNs, while E5M2 follows IEEE 754 conventions for representing special values. The efficacy of the format is demonstrated on various image and language tasks, performing as well as 16-bit training sessions. The authors cover CNNs, RNNs, and Transformer-based models without changing any of the hyperparameters from the 16-bit baseline training sessions. The study also includes large language models with up to 175B parameters. Additionally, the authors examine the post-training quantization of language models trained using 16-bit formats that resisted fixed-point int8 quantization.



---

