# Data-Free Quantization with Accurate Activation Clipping and Adaptive Batch Normalization

## Summary

Summary: The authors propose a data-free quantization method that uses accurate activation clipping and adaptive batch normalization to compress neural networks to low bit-width without accessing the original training data. The proposed method achieves high performance, including 64.33% top-1 accuracy of 4-bit ResNet18 on the ImageNet dataset and 3.7% absolute improvement over existing state-of-the-art methods.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors propose a data-free quantization method that compresses neural networks to low bit-width without accessing the original training data. Existing data-free quantization methods cause severe performance degradation due to inaccurate activation clipping range and quantization error, particularly for low bit-width. The proposed method uses accurate activation clipping (AAC) and adaptive batch normalization (ABN) to improve model accuracy. AAC exploits accurate activation information from the full-precision model, while ABN updates the batch normalization layer adaptively to address the quantization error from distribution changes. Experimental results show that the proposed method achieves surprisingly high performance, with 64.33% top-1 accuracy of 4-bit ResNet18 on the ImageNet dataset and 3.7% absolute improvement over existing state-of-the-art methods.



---

