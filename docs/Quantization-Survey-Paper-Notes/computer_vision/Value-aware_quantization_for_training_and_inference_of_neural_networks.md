# Value-aware quantization for training and inference of neural networks

## Summary

Summary: The paper proposes a novel value-aware quantization method that reduces precision for majority of data while handling small amount of large values in high precision, leading to reduced quantization errors. The proposed method offers significant memory cost reductions for activations in ResNet-152 and Inception-v3 compared to state-of-the-art methods, while maintaining the same training accuracy with 3-bit activations. The experiments also demonstrate that deep networks like Inception-v3, ResNet-101 and DenseNet-121 can be quantized for inference with 4-bit weights and activations within 1% top-1 accuracy drop.


## Target Task

computer vision

## Content

<Abstract: > We propose a novel value-aware quantization which applies aggressively reduced precision to the majority of data while separately handling a small amount of large values in high precision, which reduces total quantization errors under very low precision. We present new techniques to apply the proposed quantization to training and inference. The experiments show that our method with 3-bit activations (with 2% of large ones) can give the same training accuracy as full-precision one while offering significant (41.6% and 53.7%) reductions in the memory cost of activations in ResNet-152 and Inception-v3 compared with the state-of-the-art method. Our experiments also show that deep networks such as Inception-v3, ResNet-101 and DenseNet-121 can be quantized for inference with 4-bit weights and activations (with 1% 16-bit data) within 1% top-1 accuracy drop.



---

