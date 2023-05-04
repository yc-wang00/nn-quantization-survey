# Term quantization: furthering quantization at run time

## Summary

<Summary: >This paper proposes a method called Term Quantization (TQ) to further quantization at run time in deep neural networks (DNNs) that have already been quantized. TQ works on power-of-two terms in values and can be used for synchronized processor arrays like systolic arrays to achieve efficient parallel processing. TQ has minimal impact on DNN model performance and significantly reduces inference computation costs compared to uniform quantization for the same level of model performance. The authors evaluated TQ on various DNN architectures.


## Target Task

computer vision

## Content

<Abstract: >We present a novel technique, called Term Quantization (TQ), for furthering quantization at run time for improved computational efficiency of deep neural networks (DNNs) already quantized with conventional quantization methods. TQ operates on power-of-two terms in expressions of values. We use TQ to facilitate tightly synchronized processor arrays, such as systolic arrays, for efficient parallel processing. TQ has a minimal impact on DNN model performance, and we evaluate TQ on various DNN architectures, demonstrating significant reductions in inference computation costs compared to conventional uniform quantization for the same level of model performance.



---

