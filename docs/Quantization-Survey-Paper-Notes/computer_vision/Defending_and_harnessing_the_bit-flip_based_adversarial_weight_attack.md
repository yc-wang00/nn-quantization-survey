# Defending and harnessing the bit-flip based adversarial weight attack

## Summary

Summary: The paper discusses a new type of adversarial attack on the quantized neural network weights called Bit-Flip Attack (BFA). The authors propose that binarization-aware training and its relaxation, piece-wise clustering, can be effective countermeasures against BFA. The experiments conducted in the study indicate that defending against BFA requires significantly more effective malicious bit-flips on ResNet-20 and VGG-11 networks compared to defend-free networks to achieve the same level of prediction accuracy degradation on CIFAR-10 dataset.


## Target Task

computer vision

## Content

<Abstract: Recently, a new paradigm of the adversarial attack on the quantized neural network weights has attracted great attention, namely, the Bit-Flip based adversarial weight attack, aka. Bit-Flip Attack (BFA). In this work, we conduct comprehensive investigations on BFA and propose to leverage binarization-aware training and its relaxation – piece-wise clustering as simple and effective countermeasures to BFA. The experiments show that, for BFA to achieve the identical prediction accuracy degradation (e.g., below 11% on CIFAR-10), it requires 19.3×and480.1×more effective malicious bit-flips on ResNet-20 and VGG-11 respectively, compared to defend-free counterparts.>



---

