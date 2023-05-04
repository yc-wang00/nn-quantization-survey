# Distance-aware quantization

## Summary

<Summary: > This paper proposes a novel quantization method called Distance-Aware Quantizer (DAQ) to reduce bit-widths of weights and/or activations in neural networks. The method consists of a distance-aware soft rounding (DASR) and a temperature controller. DASR approximates discrete rounding with the kernel soft argmax to overcome the gradient mismatch issue, and the controller adjusts the temperature parameter in DASR adaptively according to the input to address the quantizer gap problem. The experimental results demonstrate that DAQ outperforms the state-of-the-art for various bit-widths.


## Target Task

computer vision

## Content

<Abstract: >We address the problem of network quantization in this paper, which is reducing bit-widths of weights and/or activations to lighten network architectures. We introduce a novel quantizer, called distance-aware quantizer (DAQ), which consists of a distance-aware soft rounding (DASR) and a temperature controller. DASR approximates the discrete rounding with the kernel soft argmax to alleviate the gradient mismatch problem. The controller adjusts the temperature parameter in DASR adaptively according to the input to address the quantizer gap problem. Experimental results show that DAQ outperforms the state of the art significantly for various bit-widths.



---

