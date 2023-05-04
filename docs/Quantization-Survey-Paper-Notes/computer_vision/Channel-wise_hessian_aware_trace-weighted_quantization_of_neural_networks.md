# Channel-wise hessian aware trace-weighted quantization of neural networks

## Summary

<Summary: >The paper introduces Channel-wise Hessian Aware trace-Weighted Quantization (CW-HAWQ), which uses Hessian traces to determine the relative sensitivity order of different channels of activations and weights. CW-HAWQ proposes using deep Reinforcement learning (DRL) Deep Deterministic Policy Gradient (DDPG) based agent to find the optimal ratios of different quantization bits and assign bits to channels according to the Hessian trace order. CW-HAWQ shows better results compared to state-of-the-art methods for multiple networks.


## Target Task

computer vision

## Content

<Abstract: > Second-order information has proven to be very effective in determining the redundancy of neural network weights and activations. Recent paper proposes to use Hessian traces of weights and activations for mixed-precision quantization and achieves state-of-the-art results. Here, we introduce Channel-wise Hessian Aware trace-Weighted Quantization (CW-HAWQ). CW-HAWQ uses Hessian trace to determine the relative sensitivity order of different channels of activations and weights. What’s more, CW-HAWQ proposes to use deep Reinforcement learning (DRL) Deep Deterministic Policy Gradient (DDPG)-based agent to ﬁnd the optimal ratios of different quantization bits and assign bits to channels according to the Hessian trace order. The number of states in CW-HAWQ is much smaller compared with traditional AutoML based mix-precision methods since we only need to search ratios for the quantization bits. Compare CW-HAWQ with state-of-the-art shows that we can achieve better results for multiple networks.



---

