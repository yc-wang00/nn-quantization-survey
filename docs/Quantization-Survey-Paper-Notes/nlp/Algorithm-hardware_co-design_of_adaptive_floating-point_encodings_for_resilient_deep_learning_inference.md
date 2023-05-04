# Algorithm-hardware co-design of adaptive floating-point encodings for resilient deep learning inference

## Summary

<Summary: > This paper presents an approach centered around a novel floating-point inspired number format, AdaptivFloat, for quantization of neural networks. The approach maximizes and optimally clips its available dynamic range at a layer granularity to create faithful encodings, exhibiting narrow to wide weight distribution, resulting in higher inference accuracies at low bit precision. Additionally, this paper presents experimental results that demonstrate per-operation energy and area that is 0.9x and 1.14x, respectively, that of an equivalent bit width NVDLA-like integer-based PE.


## Target Task

nlp

## Content

<Abstract: > Conventional hardware-friendly quantization methods like fixed-point or integer don't perform well at low precision as their dynamic ranges are not able to capture the wide data distributions seen in sequence transcription models. In this paper, we present an algorithm-hardware co-design approach centered around a novel floating-point inspired number format, AdaptivFloat that dynamically maximizes and optimally clips its available dynamic range at a layer granularity in order to create faithful encodings of neural network parameters. The results show that AdaptivFloat consistently produces higher inference accuracies compared to block floating-point, uniform, IEEE-like float or posit encodings at low bit precision (<=8-bit) across a diverse set of state-of-the-art neural networks, exhibiting narrow to wide weight distribution. At 4-bit weight precision, only a 2.1 degradation in BLEU score is observed on the AdaptivFloat-quantized Transformer network compared to total accuracy loss when encoded in the above-mentioned prominent datatypes. Furthermore, the paper presents experimental results on a DNN processing element (PE), exploiting AdaptivFloat logic in its computational datapath, that demonstrate per-operation energy and area that is 0.9x and 1.14x, respectively, that of an equivalent bit width NVDLA-like integer-based PE.



---

