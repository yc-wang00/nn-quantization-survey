# Alternating multi-bit quantization for recurrent neural networks

## Summary

<Summary: > The paper proposes quantizing both weights and activations into multiple binary codes to compress Recurrent Neural Networks (RNNs) and address issues related to deploying them on portable devices with limited resources and large latency during inference on servers with concurrent requests. The proposed method uses alternating minimization and achieves memory saving and acceleration in real inference without large loss in accuracy. The performance of this method is tested on two RNNs - LSTM and GRU in language models and is further extended to image classification tasks with excellent results.


## Target Task

computer vision

## Content

<Abstract: > Recurrent neural networks (RNNs) have achieved state-of-art performance in many applications, but they often have too many parameters to deploy on portable devices with limited resources and large latency during inference on servers with concurrent requests. To solve these issues, the authors propose quantizing the network, both weights, and activations, into multiple binary codes f



---

