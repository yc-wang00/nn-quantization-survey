# Ultra-low precision 4-bit training of deep neural networks

## Summary

<Summary: > This paper introduces new techniques and numerical representation formats that enable aggressive scaling of training systems from 8-bits to 4-bits precision. It explores the use of a novel adaptive gradient scaling technique (GradScale) that addresses challenges of insufficient range and resolution in quantized gradients. The paper also proposes solutions to mitigate the impact of bias on model convergence and examines the techniques in a variety of deep learning models with non-significant loss in accuracy while enabling significant hardware acceleration.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose a number of novel techniques and numerical representation formats that enable, for the very first time, the precision of training systems to be aggressively scaled from 8-bits to 4-bits. To enable this advance, we explore a novel adaptive Gradient Scaling technique (GradScale) that addresses the challenges of insufficient range and resolution in quantized gradients as well as explores the impact of quantization errors observed during model training. We theoretically analyze the role of bias in gradient quantization and propose solutions that mitigate the impact of this bias on model convergence. Finally, we examine our techniques on a spectrum of deep learning models in computer vision, speech and NLP. In combination with previously proposed solutions for 4-bit quantization of weight and activation tensors, 4-bit training shows non-significant loss in accuracy across application domains while enabling significant hardware acceleration (>7 over state of the art FP16 systems).



---

