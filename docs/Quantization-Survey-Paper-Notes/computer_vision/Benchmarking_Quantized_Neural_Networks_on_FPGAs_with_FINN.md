# Benchmarking Quantized Neural Networks on FPGAs with FINN

## Summary

<Summary: > This article discusses the importance of quantization in neural networks deployed on FPGAs to reduce resource usage while maintaining accuracy. The impact of mixed-precision using 2 to 8 bit precisions and weights with several parallelization configurations has been evaluated using the FINN and Brevitas frameworks. The compressed network can be better parallelized, allowing the deployed network throughput to be 62 times faster.


## Target Task

computer vision

## Content

<Abstract: > The cost of training and inference for state-of-the-art neural networks has led to a search for ways to reduce resource usage while maintaining accuracy. Lower precision can result in only minimal loss of accuracy. Deploying a neural network on low-power and low-resource hardware architectures requires reconﬁgurable architectures, which have been shown to be more powerful and ﬂexible than GPUs. This article aims to assess the impact of mixed-precision when applied to neural networks deployed on FPGAs. FINN and Brevitas frameworks are used to assess the importance of quantization and the framework quality, to evaluate the impact of quantization on neural networks using 2 to 8 bit precisions and weights with several parallelization conﬁgurations. Equivalent accuracy can be obtained using lower-precision representation and enough training, and the compressed network can be better parallelized, allowing the deployed network throughput to be 62 times faster.



---

