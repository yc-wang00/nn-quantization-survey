# Layer-wise data-free cnn compression

## Summary

Summary: The paper presents a method for compressing a pre-trained neural network without utilizing real data. They propose independent layer-wise compressions and generate training data using a pre-trained network. The method shows higher accuracy compared to existing works while utilizing much less compute for quantization compression. For pruning, the proposed method outperformed baselines with 1.5 times the sparsity rate at the same accuracy. Finally, they show how to combine their method with high-compute generative methods to achieve better results.


## Target Task

computer vision

## Content

<Abstract: >We present a computationally efficient method for compressing a trained neural network without using real data. We break the problem of data-free network compression into independent layer-wise compressions. We show how to efficiently generate layer-wise training data using only a pretrained network. We use this data to perform independent layer-wise compressions on the pretrained network. We also show how to precondition the network to improve the accuracy of our layer-wise compression method. We present results for layer-wise compression using quantization and pruning. When quantizing, we compress with higher accuracy than related works while using orders of magnitude less compute. When compressing MobileNetV2 and evaluating on ImageNet, our method outperforms existing methods for quantization at all bit-widths, achieving a+0:34% improvement in 8-bit quantization, and a stronger improvement at lower bit-widths (up to a +28:50% improvement at 5 bits). When pruning, we outperform baselines of a similar compute envelope, achieving 1:5 times the sparsity rate at the same accuracy. We also show how to combine our efficient method with high-compute generative methods to improve upon their results.



---

