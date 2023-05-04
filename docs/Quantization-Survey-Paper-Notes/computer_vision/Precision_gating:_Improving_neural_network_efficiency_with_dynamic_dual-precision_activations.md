# Precision gating: Improving neural network efficiency with dynamic dual-precision activations

## Summary

Summary: The paper proposes a trainable dynamic dual-precision quantization technique called Precision Gating (PG) for reducing the computational cost of deep neural networks. PG computes most features in low precision and only important features in higher precision, resulting in almost no accuracy loss. The proposed approach works well with various DNNs, including CNNs and RNNs, and achieves excellent results on ImageNet, mobile-friendly networks and LSTM on the Penn Tree Bank dataset. Compared to 8-bit uniform quantization, PG reduces the computational cost by 2.7 times with a 1.2% improvement in perplexity per word.


## Target Task

computer vision

## Content

<Abstract: > We propose precision gating (PG), an end-to-end trainable dynamic dual-precision quantization technique for deep neural networks. PG computes most features in a low precision and only a small proportion of important features in a higher precision to preserve accuracy. The proposed approach is applicable to a variety of DNN architectures and significantly reduces the computational cost of DNN execution with almost no accuracy loss. Our experiments indicate that PG achieves excellent results on CNNs, including statically compressed mobile-friendly networks such as ShuffleNet. Compared to the state-of-the-art prediction-based quantization schemes, PG achieves the same or higher accuracy with 2.4 times less compute on ImageNet. PG furthermore applies to RNNs. Compared to 8-bit uniform quantization, PG obtains a 1.2% improvement in perplexity per word with 2.7 times computational cost reduction on LSTM on the Penn Tree Bank dataset.



---

