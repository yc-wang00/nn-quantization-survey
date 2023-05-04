# F8net: Fixed-point 8-bit only multiplication for network quantization

## Summary

<Summary: > F8Net is a novel quantization framework that uses only fixed-point 8-bit multiplication to reduce the performance gap between quantized and full-precision models. The framework applies different fixed-point formats for weights and activations of different layers with a novel algorithm to automatically determine the right format for each layer during training. The approach achieves state-of-the-art performance and is verified on ImageNet for MobileNet V1/V2 and ResNet18/50 models compared to existing quantization techniques with INT32 multiplication or floating-point arithmetic or full-precision counterparts.


## Target Task

computer vision

## Content

<Abstract: >Neural network quantization is a promising compression technique to reduce memory footprint and save energy consumption, potentially leading to real-time inference. However, there is a performance gap between quantized and full-precision models. To reduce it, existing quantization approaches require high-precision INT32 or full-precision multiplication during inference for scaling or dequantization. This introduces a noticeable cost in terms of memory, speed, and required energy. To tackle these issues, we present F8Net, a novel quantization framework consisting of only ﬁxed-point 8-bit multiplication. To derive our method, we ﬁrst discuss the advantages of ﬁxed-point multiplication with different formats of ﬁxed-point numbers and study the statistical behavior of the associated ﬁxed-point numbers. Second, based on the statistical and algorithmic analysis, we apply different ﬁxed-point formats for weights and activations of different layers. We introduce a novel algorithm to automatically determine the right format for each layer during training. Third, we analyze a previous quantization algorithm—parameterized clipping activation (PACT)—and reformulate it using ﬁxed-point arithmetic. Finally, we unify the recently proposed method for quantization ﬁne-tuning and our ﬁxed-point approach to show the potential of our method. We verify F8Net on ImageNet for MobileNet V1/V2 and ResNet18/50. Our approach achieves comparable and better performance, when compared not only to existing quantization techniques with INT32 multiplication or ﬂoating-point arithmetic, but also to the full-precision counterparts, achieving state-of-the-art performance.



---

