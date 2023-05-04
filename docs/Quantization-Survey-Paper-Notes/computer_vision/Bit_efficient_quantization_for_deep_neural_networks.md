# Bit efficient quantization for deep neural networks

## Summary

Summary: This paper presents a comparison of post-training quantization approaches for deep neural networks that can reduce precision up to 3 bits without significant loss of accuracy. The proposed quantization methods are data-free and maintain the DNN model's optimization with the dataset distribution. The quantization approaches are analyzed across various state-of-the-art DNNs trained with ImageNet. The paper also discusses methods to decrease bit-precision beyond the quantization limits using object class clustering.


## Target Task

computer vision

## Content

<Abstract: >Quantization techniques have been a key component to designing efficient deep neural networks (DNNs), which reduce the memory usage of edge devices and optimize low-power inference. In this paper, we present a model-parameter driven comparison of post-training quantization approaches that can reduce the precision to as low as 3 bits with minimal loss of accuracy. These methods are data-free, so the resulting weight values remain tightly linked to the dataset distribution that optimizes the DNN model. Our quantization approaches are analyzed across a range of state-of-the-art DNNs that have been trained with a large dataset like ImageNet. We describe how different quantization schemes can afford local sparsity of values and a broad range-per-bit for compression. We also explore methods to decrease bit-precision beyond the quantization limits with object class clustering.



---

