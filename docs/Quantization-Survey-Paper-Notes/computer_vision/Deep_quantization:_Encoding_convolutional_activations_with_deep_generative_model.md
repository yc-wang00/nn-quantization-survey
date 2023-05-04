# Deep quantization: Encoding convolutional activations with deep generative model

## Summary

Summary: This paper proposes Fisher Vector encoding with Variational Auto-Encoder (FV-VAE), a deep architecture that quantizes local activations of convolutional layers using a deep generative model, trained in an end-to-end manner. The proposed FV-VAE is more flexible for representing the natural properties of data and yields improved generalization. The authors conduct experiments on three public datasets and report superior results compared to state-of-the-art representations, achieving the best published accuracy of 94.2% on UCF101.


## Target Task

computer vision

## Content

<Abstract: >
Deep convolutional neural networks (CNNs) are highly effective for visual recognition, but learning a universal representation from convolutional layer activations remains a fundamental problem. In this paper, the authors propose Fisher Vector encoding with Variational Auto-Encoder (FV-VAE), a deep architecture that quantizes local activations of convolutional layers using a deep generative model, trained in an end-to-end manner. The authors introduce Variational Auto-Encoder to steer a variational inference and learning in a neural network that can be easily optimized using standard stochastic gradient methods. The proposed FV-VAE is more flexible for representing the natural properties of data and yields improved generalization. The authors conduct experiments on three public datasets and report superior results compared to state-of-the-art representations, achieving to-date the best published accuracy of 94.2% on UCF101.



---

