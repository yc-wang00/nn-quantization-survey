# Qimera: Data-free quantization with synthetic boundary supporting samples

## Summary

<Summary:> Qimera is a method proposed by the authors for data-free neural network quantization. It generates synthetic boundary supporting samples using superposed latent embeddings and disentanglement mapping layer. The method improves the accuracy of model quantization in situations where the original training data is not available due to privacy or security concerns. Experimental results show that Qimera is state-of-the-art for data-free quantization.


## Target Task

computer vision

## Content

<Abstract: > Model quantization is a powerful compression method for deep neural networks that is particularly useful for edge and mobile applications. However, model quantization typically requires the original training data to maintain accuracy, which is often impossible due to privacy or security concerns. Generative methods that use synthetic samples have shown promise, but they typically rely on random noise input, which may be insufficient to capture the distribution of the original data, especially around the decision boundaries. In this paper, the authors propose Qimera, a method that uses superposed latent embeddings to generate synthetic boundary supporting samples. They also propose using an additional disentanglement mapping layer and extracting information from the full-precision model to improve the performance of these samples. Experimental results show that Qimera is state-of-the-art for data-free quantization.



---

