# Hitnet: Hybrid ternary recurrent neural network

## Summary

<Summary:> The paper investigates the accuracy degradation of RNNs under different quantization schemes and proposes a hybrid ternary RNN called HitNet which can quantize RNN models into ternary values of {-1, 0, 1} and outperforms state-of-the-art methods towards extremely quantized RNNs. The authors develop a hybrid quantization method to quantize weights and activations and introduce a sloping factor into the activation functions to address the error-sensitive problem. The proposed method improves the perplexity per word (PPW) of a ternary LSTM on Penn Tree Bank from 126 to 110.3 and a ternary GRU from 142 to 113.5.


## Target Task

speech recognition

## Content

<Abstract: >Quantization is a promising technique to reduce the model size, memory footprint, and computational cost of neural networks for employment on embedded devices with limited resources. In this paper, the authors investigate the accuracy degradation of RNNs under different quantization schemes and propose HitNet, a hybrid ternary RNN, which bridges the accuracy gap between the full precision model and the quantized model with ternary weights and activations. They develop a hybrid quantization method to quantize weights and activations, and introduce a sloping factor into the activation functions to address the error-sensitive problem. They test their method on typical RNN models and show that HitNet can quantize RNN models into ternary values of {-1, 0, 1} and significantly outperform the state-of-the-art methods towards extremely quantized RNNs. They improve the perplexity per word (PPW) of a ternary LSTM on Penn Tree Bank (PTB) corpus from 126 to 110.3 and a ternary GRU from 142 to 113.5.



---

