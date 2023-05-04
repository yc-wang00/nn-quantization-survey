# Blended coarse gradient descent for full quantization of deep neural networks

## Summary

<Summary: > This paper proposes a training algorithm for quantized deep neural networks that involves piecewise constant activation functions and discrete weights, which involves mathematical challenges. The proposed blended coarse gradient descent (BCGD) algorithm involves coarse gradient correction of a weighted average of full precision weights and their quantization which yields sufficient descent in the objective value and accelerates training.


## Target Task

computer vision

## Content

<Abstract: >Quantized deep neural networks (QDNNs) are attractive due to their much lower memory storage and faster inference speed than their regular full precision counterparts. To maintain the same performance level especially at low bit-widths, QDNNs must be retrained. Their training involves piecewise constant activation functions and discrete weights, hence mathematical challenges arise. We introduce the notion of coarse gradient and propose the blended coarse gradient descent (BCGD) algorithm, for training fully quantized neural networks. Coarse gradient is generally not a gradient of any function but an artificial ascent direction. The weight update of BCGD goes by coarse gradient correction of a weighted average of the full precision weights and their quantization (the so-called blending), which yields sufficient descent in the objective value and thus accelerates the training.



---

