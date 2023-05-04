# n-hot: Efficient bit-level sparsity for powers-of-two neural network quantization

## Summary

Summary: The paper proposes an efficient Powers-of-two (PoT) quantization scheme that introduces bit-level sparsity to reduce the number of bit operations of deep neural networks while preserving the accuracy. The proposed method uses a two-stage fine-tuning algorithm to recover the accuracy drop and experimental results show that it reduces the number of operations by about 75% and model size by 11.5% compared to the uniform method, while suppressing the accuracy drop by 0.3% at most.


## Target Task

computer vision

## Content

<Abstract: Powers-of-two (PoT) quantization reduces the number
of bit operations of deep neural networks on resource-
constrained hardware. However, PoT quantization triggers
a severe accuracy drop because of its limited representation
ability. To address this problem, we propose an efficient PoT
quantization scheme, introducing bit-level sparsity where
weights or activations are rounded to values that can be calculated
by nshift operations in multiplication. We use a two-stage
fine-tuning algorithm to recover the accuracy drop that is triggered
by introducing the bit-level sparsity. The experimental results on
an object detection model show that our proposed method suppresses
the accuracy drop by 0.3% at most while reducing the number of
operations by about 75% and model size by 11.5% compared to the
uniform method.>



---

