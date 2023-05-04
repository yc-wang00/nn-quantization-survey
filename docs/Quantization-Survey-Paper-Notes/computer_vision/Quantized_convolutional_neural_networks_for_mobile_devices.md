# Quantized convolutional neural networks for mobile devices

## Summary

Summary: The paper proposes a framework called Quantized CNN to speed up computation and reduce storage and memory overhead of CNN models. They quantize filter kernels in convolutional layers and weighting matrices in fully-connected layers to minimize estimation error of each layer's response. Experiments on ILSVRC-12 show 4-6x speed-up with 15-20x compression and a one percentage loss of classification accuracy, enabling accurate image classification within one second, even on mobile devices.


## Target Task

computer vision

## Content

<Abstract: >
In this paper, the authors propose a framework called Quantized CNN, which aims to speed up the computation and reduce the storage and memory overhead of CNN models. They quantize both the filter kernels in convolutional layers and weighting matrices in fully-connected layers to minimize the estimation error of each layer's response. The experiments conducted on the ILSVRC-12 benchmark demonstrate 4-6x speed-up with 15-20x compression and only a one percentage loss of classification accuracy. This method allows for accurate image classification within one second, even on mobile devices.



---

