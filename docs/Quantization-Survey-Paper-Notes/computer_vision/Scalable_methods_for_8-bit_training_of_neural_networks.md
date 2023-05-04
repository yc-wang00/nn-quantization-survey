# Scalable methods for 8-bit training of neural networks

## Summary

<Summary: >The paper discusses quantized neural networks (QNNs) and their effectiveness in improving network efficiency during the inference phase. The authors use theoretical analysis to show that most of the training process is robust to substantial precision reduction, with only a few specific operations requiring higher precision. They then quantize the model parameters, activations, and layer gradients to 8-bit, leaving at a higher precision only the final step in the computation of the weight gradients. Additionally, they introduce Range Batch-Normalization (BN), which is more tolerant of quantization noise and has improved computational complexity. The authors demonstrate through simulations that Range BN is equivalent to traditional batch norm with precise scale adjustments, which can be approximated analytically. This work is the first to quantize weights, activations, and a significant volume of gradients stream in all layers, including batch normalization, to 8-bit while achieving state-of-the-art results on the ImageNet-1K dataset.


## Target Task

computer vision

## Content

<Abstract: >Quantized Neural Networks (QNNs) are often used to improve network efficiency during the inference phase. Our theoretical analysis suggests that most of the training process is robust to substantial precision reduction, and points to only a few specific operations that require higher precision. Armed with this knowledge, we quantize the model parameters, activations, and layer gradients to 8-bit, leaving at a higher precision only the final step in the computation of the weight gradients. Additionally, we introduce Range Batch-Normalization (BN) which has significantly higher tolerance to quantization noise and improved computational complexity. Our simulations show that Range BN is equivalent to the traditional batch norm if a precise scale adjustment, which can be approximated analytically, is applied. To the best of the authors’ knowledge, this work is the first to quantize the weights, activations, as well as a substantial volume of the gradients stream, in all layers (including batch normalization) to 8-bit while showing state-of-the-art results over the ImageNet-1K dataset.



---

