# RMSMP: A Novel Deep Neural Network Quantization Framework with Row-wise Mixed Schemes and Multiple Precisions

## Summary

<Summary: > The paper proposes a new method for quantizing deep neural networks called RMSMP, which assigns mixed quantization schemes and multiple precisions within layers for simplified operations in hardware inference, while preserving accuracy. The quantization error can be mitigated as long as a certain portion of the weights in every layer are in higher precisions, enabling layer-wise uniformity in the hardware implementation towards guaranteed inference acceleration, while still enjoying row-wise flexibility of mixed schemes and multiple precisions to boost accuracy. The candidates of schemes and precisions are derived practically and effectively with a highly hardware-informative strategy to reduce the problem search space.


## Target Task

computer vision

## Content

<Abstract: > This work proposes a novel Deep Neural Network (DNN)
quantization framework, namely RMSMP , with a Row-wise
Mixed-Scheme and Multi-Precision approach. Specifically,
this is the first effort to assign mixed quantization schemes
and multiple precisions within layers – among rows of the
DNN weight matrix, for simplified operations in hardware
inference, while preserving accuracy. Furthermore, this paper
makes a different observation from the prior work that the
quantization error does not necessarily exhibit the layer-wise
sensitivity, and actually can be mitigated as long as a certain
portion of the weights in every layer are in higher precisions.
This observation enables layer-wise uniformity in the hardware
implementation towards guaranteed inference acceleration,
while still enjoying row-wise flexibility of mixed schemes and
multiple precisions to boost accuracy. The candidates of schemes
and precisions are derived practically and effectively with a highly
hardware-informative strategy to reduce the problem search
space.



---

