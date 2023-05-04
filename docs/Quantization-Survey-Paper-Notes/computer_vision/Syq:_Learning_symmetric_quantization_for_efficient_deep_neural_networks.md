# Syq: Learning symmetric quantization for efficient deep neural networks

## Summary

Summary: The paper introduces a quantization method that uses a symmetric codebook to reduce the loss resulting from low-precision quantization of weight parameters and/or activations in deep neural networks. The method is applied to weight subgroups determined based on their locality in the weight matrix, preserving the hardware simplicity of low-precision representations. Empirical results show that the method can improve accuracy for networks with extremely low-precision weights and activations and imposes minimal or no hardware implications to more coarse-grained approaches. The source code is available for use.


## Target Task

computer vision

## Content

<Abstract: >Inference for state-of-the-art deep neural networks is
computationally expensive, making them difﬁcult to deploy
on constrained hardware environments. An efﬁcient way
to reduce this complexity is to quantize the weight pa-
rameters and/or activations during training by approximat-
ing their distributions with a limited entry codebook. For
very low-precisions, such as binary or ternary networks
with 1-8-bit activations, the information loss from quan-
tization leads to signiﬁcant accuracy degradation due to
large gradient mismatches between the forward and back-
ward functions. In this paper, we introduce a quantization
method to reduce this loss by learning a symmetric code-
book for particular weight subgroups. These subgroups
are determined based on their locality in the weight ma-
trix, such that the hardware simplicity of the low-precision
representations is preserved. Empirically, we show that
symmetric quantization can substantially improve accu-
racy for networks with extremely low-precision weights
and activations. We also demonstrate that this representa-
tion imposes minimal or no hardware implications to more
coarse-grained approaches. Source code is available at
https://www.github.com/julianfaraone/SYQ.



---

