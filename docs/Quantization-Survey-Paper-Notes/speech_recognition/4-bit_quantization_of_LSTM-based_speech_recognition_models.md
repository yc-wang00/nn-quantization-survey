# 4-bit quantization of LSTM-based speech recognition models

## Summary

Summary: The paper investigates the impact of low-precision representations on large LSTM-based architectures for Automatic Speech Recognition (ASR). The authors demonstrate that minimal accuracy loss is achievable through the use of appropriate quantizers and initializations that are customized according to the local properties of the network. The solution is demonstrated on the Switchboard and CallHome test sets of the NIST Hub5-2000 evaluation.


## Target Task

speech recognition

## Content

<Abstract: > We investigate the impact of aggressive low-precision representations of weights and activations in large LSTM-based architectures for Automatic Speech Recognition (ASR). Using a 4-bit integer representation, a naïve quantization approach applied to the LSTM portion of these models results in significant Word Error Rate (WER) degradation. However, we show that minimal accuracy loss is achievable with an appropriate choice of quantizers and initializations. We customize quantization schemes depending on the local properties of the network, improving recognition performance while limiting computational time. We demonstrate our solution on the Switchboard (SWB) and CallHome (CH) test sets of the NIST Hub5-2000 evaluation.



---

