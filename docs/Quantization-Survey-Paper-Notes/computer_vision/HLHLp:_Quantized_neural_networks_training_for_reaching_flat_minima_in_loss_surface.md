# HLHLp: Quantized neural networks training for reaching flat minima in loss surface

## Summary

Summary: The paper proposes a novel training scheme for quantized deep neural networks, which uses alternating high-low-high-low precision coupled with an abrupt change in learning rate to reach flat minima in the loss surface. The proposed technique demonstrates superior performance for convolutional neural networks and achieves state-of-the-art results for recurrent neural network-based language modeling with 2-bit weight and activation compared to previous fine-tuning-based quantization schemes.


## Target Task

computer vision

## Content

<Abstract: >
Quantized deep neural networks (QDNNs) are important for efficient implementations. To this end, we propose a novel training scheme that employs high-low-high-low precision in an alternating manner for network training, coupled with an abrupt change in the learning rate at each stage for coarse- or fine-tuning, to reach flat minima in the loss surface with the aid of quantization noise. Using this proposed training technique, we demonstrate significant performance improvements for convolutional neural networks when compared to previous fine-tuning-based quantization schemes, and we achieve state-of-the-art results for recurrent neural network-based language modeling with 2-bit weight and activation.



---

