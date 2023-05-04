# And the bit goes down: Revisiting the quantization of neural networks

## Summary

Summary: The paper introduces a vector quantization method to reduce the memory usage of convolutional network architectures. It focuses on preserving the quality of the reconstruction of the network outputs instead of its weights. By using byte-aligned codebooks, the method allows for efficient inference on CPU, and it only requires a set of unlabelled data at quantization time. The approach was validated by quantizing a ResNet-50 model to a 5MB memory size while maintaining a top-1 accuracy of 76.1% on ImageNet object classification and compressing a Mask R-CNN with a 26x factor.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we address the problem of reducing the memory footprint of convolutional network architectures. We introduce a vector quantization method that aims at preserving the quality of the reconstruction of the network outputs rather than its weights. Our method only requires a set of unlabelled data at quantization time and allows for efficient inference on CPU by using byte-aligned codebooks to store the compressed weights. We validate our approach by quantizing a high performing ResNet-50 model to a memory size of 5MB while preserving a top-1 accuracy of 76.1% on ImageNet object classification and by compressing a Mask R-CNN with a 26x factor.



---

