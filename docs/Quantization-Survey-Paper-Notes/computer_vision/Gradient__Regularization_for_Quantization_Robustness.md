# Gradient  Regularization for Quantization Robustness

## Summary

<Summary: >The paper discusses the effect of quantizing weights and activations in neural networks on loss and presents a regularization method to improve robustness against post-training quantization. The proposed approach allows storing a single set of weights that can be quantized to different bit-widths. The regularization scheme is validated experimentally on various architectures on CIFAR-10 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract: > We analyze the effect of quantizing weights and activations of neural networks on their loss and derive a simple regularization scheme that improves robustness against post-training quantization. Our approach enables storing a single set of weights that can be quantized on-demand to different bit-widths. By modeling quantization as a `1-bounded perturbation, the first-order term in the loss expansion can be regularized using the `1-norm of gradients. We experimentally validate the effectiveness of our regularization scheme on different architectures on CIFAR-10 and ImageNet datasets.



---

