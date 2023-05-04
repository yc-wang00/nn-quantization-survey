# Mixed Precision Low-Bit Quantization of Neural Network Language Models for Speech Recognition

## Summary

Summary: This paper proposes novel mixed precision neural network language model quantization methods that automatically learn optimal local precision choices for LSTM-RNN and Transformer based LMs, providing a solution to reduce complex and expensive models' size. Current quantization methods based on uniform precision fail to account for performance sensitivity at different parts of LMs to quantization errors.


## Target Task

nlp

## Content

Abstract: State-of-the-art language models (LMs) represented by long-short term memory recurrent neural networks (LSTM-RNNs) and Transformers are becoming increasingly complex and expensive for practical applications. Low-bit neural network quantization provides a powerful solution to dramatically reduce their model size. Current quantization methods are based on uniform precision and fail to account for the varying performance sensitivity at different parts of LMs to quantization errors. To this end, novel mixed precision neural network LM quantization methods are proposed in this paper. The optimal local precision choices for LSTM-RNN and Transformer based neural LMs are automatically learned using three techniques.



---

