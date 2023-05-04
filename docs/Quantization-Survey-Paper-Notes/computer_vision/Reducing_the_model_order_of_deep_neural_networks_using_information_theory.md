# Reducing the model order of deep neural networks using information theory

## Summary

<Summary: >The paper proposes a method to compress deep neural networks by estimating the Fisher Information metric through a stochastic optimization method. The method involves removing unimportant parameters and using non-uniform fixed point quantization to assign more bits to parameters with higher Fisher Information estimates. The proposed method outperforms existing methods for network pruning and quantization and was evaluated on a classification task with a convolutional neural network trained on the MNIST dataset.


## Target Task

computer vision

## Content

<Abstract:> In this research paper, a method to compress deep neural networks by reducing the complexity of DNNs has been proposed using the Fisher Information metric by estimating it through a stochastic optimization method. The authors first remove unimportant parameters and then use non-uniform fixed point quantization to assign more bits to parameters with higher Fisher Information estimates. The performance of the proposed method was evaluated on a classification task with a convolutional neural network trained on the MNIST dataset, and experimental results showed that this method outperforms existing methods for both network pruning and quantization.



---

