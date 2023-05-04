# Effective quantization methods for recurrent neural networks

## Summary

Summary: This paper proposes a method for quantizing the structure of gates and interlinks in LSTM and GRU cells, as well as balanced quantization methods for weights to reduce performance degradation. The experiments on PTB and IMDB datasets prove the effectiveness of these methods and show that the performance matches or surpasses the previous state-of-the-art of quantized RNN.


## Target Task

nlp

## Content

<Abstract:>
Reducing bit-widths of weights, activations, and gradients of a Neural Network can shrink its storage size and memory usage, and also allow for faster training and inference by exploiting bitwise operations. However, previous attempts for quantization of RNNs show considerable performance degradation when using low-bit-width weights and activations. In this paper, we propose methods to quantize the structure of gates and interlinks in LSTM and GRU cells. In addition, we propose balanced quantization methods for weights to further reduce performance degradation. Experiments on PTB and IMDB datasets confirm effectiveness of our methods as performances of our models match or surpass the previous state-of-the-art of quantized RNN.



---

