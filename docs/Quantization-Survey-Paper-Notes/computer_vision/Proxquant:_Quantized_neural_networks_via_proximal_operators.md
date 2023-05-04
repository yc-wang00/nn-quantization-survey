# Proxquant: Quantized neural networks via proximal operators

## Summary

Summary: The paper proposes a new approach for quantizing neural networks called ProxQuant. ProxQuant uses a principled, regularized approach to optimize low-precision weights using the prox-gradient method. Back-propagation is performed on the full-precision vector and a prox-operator is applied to encourage quantizedness. Theoretical analyses show that ProxQuant converges to stationary points under mild smoothness assumptions, outperforming state-of-the-art results on binary quantization for ResNets and LSTMs, and equivalent to state-of-the-art for multi-bit quantization.


## Target Task

computer vision

## Content

<Abstract: >To make deep neural networks feasible in resource-constrained environments (such as mobile devices), it is beneficial to quantize models by using low-precision weights. One common technique for quantizing neural networks is the straight-through gradient method, which enables back-propagation through the quantization mapping. Despite its empirical success, little is understood about why the straight-through gradient method works. Building upon a novel observation that the straight-through gradient method is in fact identical to Nesterov's dual-averaging algorithm on a quantization constrained optimization problem, we propose a more principled alternative approach, called ProxQuant, that formulates quantized network training as a regularized learning problem instead and optimizes it via the prox-gradient method. ProxQuant does back-propagation on the underlying full-precision vector and applies an efficient prox-operator in between stochastic gradient steps to encourage quantizedness. For quantizing ResNets and LSTMs, ProxQuant outperforms state-of-the-art results on binary quantization and is on par with state-of-the-art on multi-bit quantization. We further perform theoretical analyses showing that ProxQuant converges to stationary points under mild smoothness assumptions, whereas variants such as lazy prox-gradient method can fail to converge in the same setting.



---

