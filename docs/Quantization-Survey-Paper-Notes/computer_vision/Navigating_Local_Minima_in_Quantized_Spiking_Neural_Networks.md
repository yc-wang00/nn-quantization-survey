# Navigating Local Minima in Quantized Spiking Neural Networks

## Summary

<Summary: > The paper discusses the challenges faced by Spiking and Quantized Neural Networks when trained using error backpropagation. It proposes a solution to overcome the absence of gradient signals by periodically boosting the Learning Rate (LR) during training. A cosine-annealed LR schedule coupled with weight-independent adaptive moment estimation is applied to Quantized Spiking Neural Networks (QSNNs), and a rigorous empirical evaluation of this technique is performed on high precision and 4-bit quantized SNNs across three datasets, demonstrating close to state-of-the-art performance on the more complex datasets.


## Target Task

computer vision

## Content

<Abstract: > Spiking and Quantized Neural Networks (NNs) face challenges when trained using error backpropagation due to the absence of gradient signals when applying hard thresholds. To overcome this, biased gradient estimators are used, such as surrogate gradients and Straight-Through Estimators (STEs). However, such noise increases the difficulty of finding optima in loss landscapes, especially during later stages of optimization. By periodically boosting the Learning Rate (LR) during training, the network can navigate unexplored solution spaces that would otherwise be difficult to reach due to local minima, barriers, or flat surfaces. This paper presents a systematic evaluation of a cosine-annealed LR schedule coupled with weight-independent adaptive moment estimation as applied to Quantized Spiking Neural Networks (QSNNs). They provide a rigorous empirical evaluation of this technique on high precision and 4-bit quantized SNNs across three datasets, demonstrating close to state-of-the-art performance on the more complex datasets.



---

