# Quantized memory-augmented neural networks

## Summary

Summary: This paper focuses on quantizing Memory-augmented Neural Networks (MANNs) and proposes a quantization method to address the performance degradation caused mainly due to memory addressing. The proposed method achieves a computation-energy gain of 22 × with 8-bit fixed-point and binary quantization compared to floating-point implementation, and results in a model named Quantized MANN (Q-MANN) that improves error rates by 46% and 30% with 8-bit fixed-point and binary quantization, respectively, compared to the MANN quantized using conventional techniques on the bAbI dataset.


## Target Task

computer vision

## Content

<Abstract: >Memory-augmented neural networks (MANNs) refer to a class of neural network models equipped with external memory. These neural networks outperform conventional recurrent neural networks (RNNs) in terms of learning long-term dependency, allowing them to solve intriguing AI tasks that would otherwise be hard to address. This paper concerns the problem of quantizing MANNs. In this paper, we identify memory addressing as the main reason for the performance degradation and propose a robust quantization method for MANNs to address the challenge. In our experiments, we achieved a computation-energy gain of 22 × with 8-bit fixed-point and binary quantization compared to the floating-point implementation. Measured on the bAbI dataset, the resulting model, named the quantized MANN (Q-MANN), improved the error rate by 46% and 30% with 8-bit fixed-point and binary quantization, respectively, compared to the MANN quantized using conventional techniques.



---

