# A spike in performance: Training hybrid-spiking neural networks with quantized activation functions

## Summary

Summary: The authors of the paper propose a new method for training hybrid-spiking networks that outperforms state-of-the-art recurrent architectures while maintaining a high level of accuracy. The new approach involves gradually transitioning between non-spiking and spiking regimes and significantly improves energy efficiency by reducing activities to an average of 3.74 bits while multiplying each weight by 1.26 significant bits.


## Target Task

computer vision

## Content

<Abstract: >The machine learning community is interested in the energy efficiency of neural networks, and Spiking Neural Networks (SNNs) are being explored as a promising approach due to their activation levels being quantized into temporally sparse, one-bit values. However, maintaining state-of-the-art accuracy when converting a non-spiking network to an SNN has posed a challenge, primarily due to spikes having only a single bit of precision. In this paper, the authors propose a new method of training hybrid-spiking networks by smoothly interpolating between non-spiking and spiking regimes, and show that it outperforms state-of-the-art recurrent architectures while reducing activities to at most 3.74 bits on average with 1.26 significant bits multiplying each weight. The paper presents a discussion on how these methods can significantly improve the energy efficiency of neural networks.



---

