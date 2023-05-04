# Task-aware quantization network for JPEG image compression

## Summary

<Summary: >The paper proposes a deep neural network for JPEG image compression that can predict image-specific optimized quantization tables by adjusting the objective function of the network. They learn a differentiable loss function to address non-differentiable components in the encoder and evaluate the proposed algorithm using multiple task-specific losses. The effectiveness of the algorithm is demonstrated in different tasks including adaptive quantization and bitrate approximation.


## Target Task

computer vision

## Content

<Abstract: >We propose a deep neural network for JPEG image compression that predicts image-specific optimized quantization tables compatible with the standard JPEG encoder and decoder. We provide the capability to learn task-specific quantization tables in a principled way by adjusting the objective function of the network. We address the challenge of non-differentiable components in the encoder, such as run-length encoding and Huffman coding, by learning a differentiable loss function that approximates bitrates using simple network blocks – two MLPs and an LSTM. We evaluate the proposed algorithm using multiple task-specific losses, and demonstrate its effectiveness in different tasks. Keywords: JPEG image compression, adaptive quantization, bitrate approximation.



---

