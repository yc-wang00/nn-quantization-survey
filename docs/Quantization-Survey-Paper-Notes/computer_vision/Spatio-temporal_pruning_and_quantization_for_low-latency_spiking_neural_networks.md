# Spatio-temporal pruning and quantization for low-latency spiking neural networks

## Summary

<Summary: >The paper introduces spatio-temporal pruning and quantization as techniques for enhancing the efficiency of Spiking Neural Networks (SNNs). The proposed method uses structured spatial pruning and gradual reduction of timesteps in temporal pruning. The method achieves up to 10-14X model size compression and 3-30X reduced latency compared to other SNNs while maintaining a high level of accuracy. The paper also finds that post-training weight quantization with up to 5-bit quantization does not significantly affect network performance.


## Target Task

computer vision

## Content

<Abstract: >Spiking Neural Networks (SNNs) present a promising alternative to traditional deep learning methods due to their computationally efficient sparse event-driven information processing. However, SNNs suffer from high inference latency, especially for real-time applications. This paper proposes spatio-temporal pruning and quantization for SNNs to enhance their efficiency. Structured spatial pruning is performed by identifying layer-wise significant dimensions using principal component analysis, which leads to 10-14X model size compression. Additionally, gradual reduction of timesteps in temporal pruning reduces the latency of inference. The proposed spatio-temporally pruned SNNs perform with 89.04% and 66.4% accuracy on CIFAR10 and CIFAR100, respectively, while achieving 3-30X reduced latency compared to other state-of-the-art SNNs. Furthermore, post-training weight quantization does not significantly affect network performance for up to 5-bit quantization.



---

