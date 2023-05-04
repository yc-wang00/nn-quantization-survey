# Q-spinn: A framework for quantizing spiking neural networks

## Summary

Summary: This paper proposes Q-SpiNN, a new quantization framework that quantizes different parameters of Spiking Neural Networks depending on their significance to the accuracy, explores different combinations of quantization schemes, and selects the Pareto-optimal model for a good memory-accuracy trade-off. Q-SpiNN reduces memory footprint while maintaining accuracy across different datasets.


## Target Task

computer vision

## Content

<Abstract: >A prominent technique for reducing the memory footprint of Spiking Neural Networks (SNNs) without decreasing the accuracy significantly is quantization. However, the state-of-the-art only focus on employing the weight quantization directly from a specific quantization scheme, i.e., either the post-training quantization (PTQ) or the in-training quantization (ITQ), and do not consider (1) quantizing other SNN parameters (e.g., neurons’ membrane potential), (2) exploring different combinations of quantization approaches (i.e., quantization schemes, precision levels, and rounding schemes), and (3) selecting the SNN model with a good memory-accuracy trade-off at the end. Towards this, we propose Q-SpiNN, a novel quantization framework for memory-efﬁcient SNNs. The key mechanisms of the Q-SpiNN are: (1) employing quantization for different SNN parameters based on their significance to the accuracy, (2) exploring different combinations of quantization schemes, precision levels, and rounding schemes to ﬁnd efficient SNN model candidates, and (3) developing an algorithm that quantifies the benefit of the memory-accuracy trade-off obtained by the candidates and selects the Pareto-optimal one. The experimental results show that, for the unsupervised network, the Q-SpiNN reduces the memory footprint by ca. 4x, while maintaining the accuracy within 1% from the baseline on the MNIST dataset. For the supervised network, the Q-SpiNN reduces the memory by ca. 2x, while keeping the accuracy within 2% from the baseline on the DVS-Gesture dataset.



---

