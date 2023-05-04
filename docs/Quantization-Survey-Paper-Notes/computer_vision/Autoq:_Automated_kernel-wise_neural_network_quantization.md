# Autoq: Automated kernel-wise neural network quantization

## Summary

<Summary: >This paper proposes a hierarchical-DRL-based kernel-wise network quantization technique, AutoQ, to automatically search a QBN for each weight kernel, and choose another QBN for each activation layer. AutoQ reduces inference latency by 54.06% and decreases inference energy consumption by 50.69% on average, while achieving the same inference accuracy as models quantized by the state-of-the-art DRL-based schemes.


## Target Task

computer vision

## Content

<Abstract: >Network quantization is one of the most hardware friendly techniques to enable
the deployment of convolutional neural networks (CNNs) on low-power mobile devices. Recent network quantization techniques quantize each weight kernel in a
convolutional layer independently for higher inference accuracy, since the weight kernels in a layer exhibit different variances and hence have different amounts
of redundancy. The quantization bitwidth or bit number (QBN) directly decides
the inference accuracy, latency, energy and hardware overhead. To effectively
reduce the redundancy and accelerate CNN inferences, various weight kernels
should be quantized with different QBNs. However, prior works use only one
QBN to quantize each convolutional layer or the entire CNN, because the design
space of searching a QBN for each weight kernel is too large. The hand-crafted
heuristic of the kernel-wise QBN search is so sophisticated that domain experts
can obtain only sub-optimal results. It is difﬁcult for even deep reinforcement
learning (DRL) Deep Deterministic Policy Gradient (DDPG)-based agents to ﬁnd
a kernel-wise QBN conﬁguration that can achieve reasonable inference accuracy.
In this paper, we propose a hierarchical-DRL-based kernel-wise network quantization technique, AutoQ, to automatically search a QBN for each weight kernel,
and choose another QBN for each activation layer. Compared to the models quan-
tized by the state-of-the-art DRL-based schemes, the same models quantized by
AutoQ reduce the inference latency by 54.06%, and decrease the inference energy
consumption by 50.69% averagely, while achieving the same inference accuracy.



---

