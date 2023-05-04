# Training quantized neural networks with a full-precision auxiliary module

## Summary

Summary: The paper proposes a solution to the difficulty of propagating gradients through a low-precision network by suggesting training the network with a full-precision auxiliary module, which creates additional full-precision routes to update the parameters of the low-precision model, without adding computational complexity at the inference time. The authors evaluate the proposed method on image classification and object detection over various quantization approaches and report consistent performance improvement. They achieve near lossless performance to the full-precision model using a 4-bit detector.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors propose a solution to the difficulty in propagating gradients through a low-precision network due to the non-differentiable quantization function. They suggest training the low-precision network with a full-precision auxiliary module, which creates additional full-precision routes to update the parameters of the low-precision model, thus making the gradient back-propagation more easily. They discard the auxiliary module at the inference time without introducing any computational complexity to the low-precision network. The proposed method has been evaluated on image classification and object detection over various quantization approaches, and consistent performance increase has been observed. The authors achieve near lossless performance to the full-precision model by using a 4-bit detector, which is of great practical value.



---

