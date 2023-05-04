# Post-training weighted quantization of neural networks for language models

## Summary

Summary: The paper proposes a non-uniform quantization scheme, namely binary-coding-based quantization for language models with significant memory. The scheme achieves high compression and effective computation without significant accuracy degradation. The paper develops quantization optimization approaches that consider the importance of each parameter. The methods demonstrate that post-training quantization and weight magnitude representation can significantly improve accuracy compared to other schemes. The proposed quantization is applied to several language models, including AWD-LSTM, Transformer, BERT, and DistilBERT, achieving 2-4 bits per weight with reasonable accuracy degradation.


## Target Task

nlp

## Content

<Abstract: As a practical model compression technique, parameter quantization is effective especially for language models associated with a large memory footprint. In this paper, we propose a non-uniform quantization scheme, specifically binary-coding-based quantization, for high compression ratio and efficient computations while avoiding large accuracy degradation by uniform quantization. We derive quantization optimization methods to take into account the importance of each parameter and demonstrate that for post-training quantization, weight magnitude can represent importance and improve model accuracy significantly compared to previous schemes lacking importance considerations. For various language models including BERT, DistilBERT, AWD-LSTM, and Transformer, we achieve 2-4 bits per weight by our proposed post-training quantization with reasonable accuracy degradation.>



---

