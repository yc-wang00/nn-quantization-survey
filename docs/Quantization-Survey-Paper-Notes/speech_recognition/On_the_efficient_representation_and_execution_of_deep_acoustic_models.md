# On the efficient representation and execution of deep acoustic models

## Summary

<Summary: > The paper proposes a quantization scheme to reduce the resolution of a neural network's parameters from 32-bit floating point values to 8-bit integer values for memory savings and optimized hardware instructions. A 'quantization aware' training process is proposed to recover most of the accuracy loss caused by quantization. The techniques are validated on a long short-term memory-based acoustic model for a speech recognition task and can be applied to other deep learning models and domains.


## Target Task

speech recognition

## Content

<Abstract: > In this paper, we propose a simple and computationally efficient quantization scheme to reduce the resolution of the parameters of a neural network from 32-bit floating point values to 8-bit integer values. This enables significant memory savings and the use of optimized hardware instructions for integer arithmetic, thus reducing the cost of inference. We also propose a 'quantization aware' training process to recover most of the loss in accuracy introduced by quantization. We validate our techniques by applying them to a long short-term memory-based acoustic model on a large vocabulary speech recognition task. The proposed techniques can be applied to other deep learning models and domains.



---

