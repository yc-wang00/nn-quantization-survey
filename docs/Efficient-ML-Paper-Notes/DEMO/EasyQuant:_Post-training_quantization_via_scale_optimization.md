# EasyQuant: Post-training quantization via scale optimization

## Summary

<Summary: >The paper proposes a post-training quantization technique called EasyQuant (EQ) that optimizes the scales of weights and activations to lower the bit width to INT7 for both weights and activations. The experimental results show that EQ outperforms TensorRT and achieves near INT8 accuracy in 7 bits width post-training, making it suitable for ARM deployment.


## Target Task

Target: computer vision

## Content

<Abstract: >The paper presents a post-training quantization method called EasyQuant (EQ) that achieves comparable accuracy to training-based quantization methods. EQ optimizes scales of weights and activations for all layers and lowers down the bit width to INT7 for weights and activations. The experimental results show that EQ outperforms the TensorRT method and achieves near INT8 accuracy in 7 bits width post-training. Keywords: Post-training quantization, scale optimization, INT7 inference, ARM deployment.



---

