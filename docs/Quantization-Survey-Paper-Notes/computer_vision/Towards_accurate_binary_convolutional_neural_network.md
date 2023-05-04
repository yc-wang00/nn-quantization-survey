# Towards accurate binary convolutional neural network

## Summary

Summary: The paper proposes a scheme called ABC-Net for training binary convolutional neural networks (CNNs) with weights and activations constrained to {-1, +1} at run-time. The proposed scheme addresses the challenge of severe prediction accuracy degradation in binarizing CNNs by approximating full-precision weights with the linear combination of multiple binary weight bases and employing multiple binary activations to reduce information loss. The resulting ABC-Net is shown to achieve performance closer to full-precision CNNs and even comparable prediction accuracy on the ImageNet and forest trail datasets, provided adequate binary weight bases and activations are used.


## Target Task

computer vision

## Content

<Abstract: >
We introduce a novel scheme to train binary convolutional neural networks (CNNs) – CNNs with weights and activations constrained to {-1,+1} at run-time. In this paper, we address the severe prediction accuracy degradation issue in the previous works on binarizing CNNs with two major innovations: (1) approximating full-precision weights with the linear combination of multiple binary weight bases; (2) employing multiple binary activations to alleviate information loss. The resulting binary CNN, denoted as ABC-Net, is shown to achieve much closer performance to its full-precision counterpart, and even reach the comparable prediction accuracy on ImageNet and forest trail datasets, given adequate binary weight bases and activations.



---

