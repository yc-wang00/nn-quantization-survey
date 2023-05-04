# Sub-8-bit quantization aware training for 8-bit neural network accelerator with on-device speech recognition

## Summary

Summary: The paper proposes a sub-8-bit quantization-aware training scheme called S8BQAT for 8-bit neural network accelerators. The scheme uses quantization centroids derived from a 32-bit baseline and a Multi-Regional Absolute Cosine regularizer to augment training loss. Additionally, the paper introduces a hard compressor to improve convergence rate. The proposed scheme was applied on speech recognition tasks using RNN-T architecture and resulted in a reduction of word error rate by 4-16% while improving latency by 5%.


## Target Task

speech recognition

## Content

<Abstract: > We present a novel sub-8-bit quantization-aware training (S8BQAT) scheme for 8-bit neural network accelerators. With the quantization centroids derived from a 32-bit baseline, we augment training loss with a Multi-Regional Absolute Cosine (MRACos) regularizer that aggregates weights towards their nearest centroid, effectively acting as a pseudo compressor. Additionally, a periodically invoked hard compressor is introduced to improve the convergence rate by emulating runtime model weight quantization. We apply S8BQAT on speech recognition tasks using Recurrent Neural Network-Transducer (RNN-T) architecture. With S8BQAT, we are able to increase the model parameter size to reduce the word error rate by 4-16% relatively, while still improving latency by 5%.



---

