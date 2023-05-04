# Convolutional neural network quantization using generalized gamma distribution

## Summary

<Summary: >This paper proposes a novel quantization algorithm for hardware accelerators in CNNs, which determines the optimal fractional bit length for weights and biases and quantization step size using asymptotical closed form solution of generalized gamma distribution (GGD). The algorithm outperforms other quantization schemes in terms of signal-to-quantization-noise ratio (SQNR).


## Target Task

computer vision

## Content

<Abstract: >In this paper, a novel quantization algorithm for energy-efficient deployment of hardware accelerators for convolutional neural networks (CNN) is proposed. The proposed algorithm determines the optimal bit length of the fractional part for weights and biases to minimize the quantization error over their distribution. For feature-map data, the sample distribution is well approximated with the generalized gamma distribution (GGD), and the optimal quantization step size can be obtained through the asymptotical closed form solution of GGD. The proposed algorithm outperforms other quantization schemes previously proposed for CNNs in terms of signal-to-quantization-noise ratio (SQNR).



---

