# Actnn: Reducing training memory footprint via 2-bit activation compressed training

## Summary

Summary: The ActNN framework is proposed in this research paper, which is a memory-efficient training method that reduces the memory footprint required while training neural networks. It quantizes activations randomly for back propagation and utilizes mixed-precision quantization strategies to take advantage of activation's heterogeneity. The framework requires less memory and provides negligible accuracy loss, allowing for a larger batch size during training. The convergence of ActNN is proved for general network architectures, and quantization's impact on convergence is also characterized through gradient variance. It can be applied to existing dynamic graph frameworks like PyTorch by substituting the layers.


## Target Task

computer vision

## Content

<Abstract: >
In this research paper, the authors propose ActNN, a memory-efficient training framework that reduces the training memory footprint of neural networks. ActNN stores randomly quantized activations for back propagation and utilizes mixed-precision quantization strategies that exploit the activation's heterogeneity across feature dimensions, samples, and layers. The proposed framework provides negligible accuracy loss and reduces the activation's memory footprint by 12 times, enabling training with a 6.6 to 14 times larger batch size. The authors prove the convergence of ActNN for general network architectures and characterize the impact of quantization on the convergence via an exact expression for the gradient variance. The proposed method can be readily applied to existing dynamic graph frameworks, such as PyTorch, by substituting the layers.



---

