# Tensorquant: A simulation toolbox for deep neural network quantization

## Summary

<Summary: > The paper discusses the advantages of using low precision numerical representations in deep neural networks (DNN), and how such compact representations can be implemented on hardware accelerators like FPGAs. The authors introduce TensorQuant, a quantization toolbox for the TensorFlow framework, which supports generic quantization methods and allows experimental evaluation of the impact of quantization on DNN topologies. They show an analysis of fix-point quantizations of popular CNN topologies using TensorQuant toolset.


## Target Task

computer vision

## Content

<Abstract: >Recent research shows that low precision numerical representations of the training and test data, weights, and gradients in deep neural networks (DNN) do not lead to a general loss in accuracy. Such compact representations lead to a significant reduction of communication bottleneck in distributed DNN training and faster neural network implementations on hardware accelerators like FPGAs. However, the optimal choice of the quantization method and number of coding bits is topology-dependent, and there is no general theory available to derive the optimal quantization during the design of a DNN topology. Therefore, in this paper, the authors present TensorQuant - a quantization toolbox for the TensorFlow framework, allowing a transparent quantization simulation of existing DNN topologies during training and inference. TensorQuant supports generic quantization methods and allows experimental evaluation of the impact of the quantization on single layers as well as the full topology. The authors show an analysis of fix-point quantizations of popular CNN topologies using TensorQuant toolset.



---

