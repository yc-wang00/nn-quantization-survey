# Understanding straight-through estimator in training activation quantized neural nets

## Summary

<Summary: > The paper discusses the issue of a vanishing gradient when training activation quantized neural networks and proposes the use of a straight-through estimator (STE) in the backward pass to provide a non-trivial gradient. The paper provides theoretical justification for the concept of STE and warns that a poor choice of STE may lead to instability in the training algorithm near certain local minima as confirmed by CIFAR-10 experiments.


## Target Task

computer vision

## Content

<Abstract: > Training activation quantized neural networks involves minimizing a piecewise constant function whose gradient vanishes almost everywhere, which is undesirable for the standard back-propagation or chain rule. An empirical way around this issue is to use a straight-through estimator (STE) in the backward pass only, so that the “gradient” through the modified chain rule becomes non-trivial. In this paper, we provide the theoretical justification of the concept of STE by answering this question. We further show that a poor choice of STE leads to instability of the training algorithm near certain local minima, which is verified with CIFAR-10 experiments.



---

