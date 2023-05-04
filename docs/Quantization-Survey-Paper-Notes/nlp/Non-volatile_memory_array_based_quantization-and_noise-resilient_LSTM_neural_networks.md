# Non-volatile memory array based quantization-and noise-resilient LSTM neural networks

## Summary

Summary: The paper proposes the application of quantization-aware training algorithm to LSTM models in cloud and edge computing and shows that 4-bit NVM weights and 4-bit ADC/DACs are enough to produce equivalent LSTM network performance as floating-point baseline. The proposed LSTM accelerator for inference is much more efficient (2.4x computing efficiency and 40x area efficiency) than traditional digital approaches like GPU, FPGA, and ASIC.


## Target Task

nlp

## Content

Abstract: In cloud and edge computing models, it is important that compute devices at the edge be as power efficient as possible. Long short-term memory (LSTM) neural networks have been widely used for natural language processing, time series prediction, and many other sequential data tasks. In this paper, we focus on the application of quantization-aware training algorithm to LSTM models, and the benefits these models bring in terms of resilience against both quantization error and analog device noise. We have shown that only 4-bit NVM weights and 4-bit ADC/DACs are needed to produce equivalent LSTM network performance as floating-point baseline. Reasonable levels of ADC quantization noise and weight noise can be naturally tolerated within our NVM-based quantized LSTM network. Benchmark analysis of our proposed LSTM accelerator for inference has shown at least 2.4× better computing efficiency and 40× higher area efficiency than traditional digital approaches (GPU, FPGA, and ASIC).



---

