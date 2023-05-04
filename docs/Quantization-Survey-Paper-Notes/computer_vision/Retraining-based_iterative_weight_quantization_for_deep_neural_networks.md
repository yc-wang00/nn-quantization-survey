# Retraining-based iterative weight quantization for deep neural networks

## Summary

Summary: The paper presents an iterative technique for weight quantization, which involves weight quantization and retraining the model with full precision weights. This approach achieves high model compression ratios without altering the training algorithm. The results show that an LSTM model using 1-bit quantized weights suffices for a PTB dataset without accuracy degradation, which outperforms previous methods that required 2-4 bits for quantized weights.


## Target Task

computer vision

## Content

<Abstract: > Model compression has gained attention for reducing hardware resource requirements while maintaining accuracy of deep neural networks. Quantization is an effective method for model compression, but minimizing the number of bits to represent parameters has been a challenge. We present an iterative technique for weight quantization that achieves a high compression ratio without modifications to the training algorithm. Our proposed technique involves weight quantization followed by retraining the model with full precision weights, generating new sets of weights that can be quantized with decreasing loss at each iteration. We also show that quantization can efficiently leverage pruning. Our experimental results demonstrate that an LSTM model using 1-bit quantized weights suffices for a PTB dataset without accuracy degradation, while previous methods required at least 2-4 bits for quantized weights.



---

