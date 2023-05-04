# SWIS--Shared Weight bIt Sparsity for Efficient Neural Network Acceleration

## Summary

Summary: The paper proposes a quantization framework called SWIS which achieves up to 54.3% point accuracy improvement compared to weight truncation. It achieves improved performance and storage compression through an offline weight decomposition and scheduling algorithm. It uses configurable, non-consecutive shift values on small groups of weights to significantly reduce the effective required bitwidth, achieving up to 3.7× neural network weight compression compared to conventional quantization approaches. The proposed SWIS architecture achieves up to 6× improvement in inference latency (energy) compared to state-of-the-art bit-serial accelerators of same size. The SWIS architecture reduces the number of memory weight to activation accesses by up to 10x in some convolutional layers by using different precision weights and activations and reducing precision more on the weight side.


## Target Task

computer vision

## Content

<Abstract: > Quantization is important for efficient neural network computing systems, but only a subset of applications can take advantage of such aggressive precision reduction. SWIS - Shared Weight bIt Sparsity is a quantization framework that achieves up to 54.3% point accuracy improvement compared to weight truncation. It delivers improved performance and storage compression via an offline weight decomposition and scheduling algorithm. With configurable, non-consecutive shift values on small groups of weights, SWIS can significantly reduce the effective required bitwidth. It achieves up to 3.7×neural network weight compression compared to conventional quantization approaches at similar inference accuracy. Additionally, the proposed SWIS architecture achieves up to 6×(1.8×) improvement in inference latency (energy) compared to state-of-the-art bit-serial accelerators of same size. Finally, SWIS architecture uses different precision weights and activations and reduces precision more on the weight side, reducing the number of memory weight to activation accesses by up to 10x in some convolutional layers.



---

