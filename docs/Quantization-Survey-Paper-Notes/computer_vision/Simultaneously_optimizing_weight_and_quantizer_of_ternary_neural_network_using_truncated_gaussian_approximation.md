# Simultaneously optimizing weight and quantizer of ternary neural network using truncated gaussian approximation

## Summary

Summary: The paper introduces a ternarized neural network training method to optimize both weights and quantizer during training, thereby reducing model size and computational cost. The authors incorporate the threshold of weight ternarization using truncated Gaussian approximation and optimize it through back-propagation, achieving a 3.9/2.52/2.16% accuracy degradation on the ImageNet classification task using ternarized ResNet-18/34/50 with the first and last layer ternarized.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors propose a novel ternarized neural network training method that simultaneously optimizes both weights and quantizer during training, enabling a significant reduction in model size and computational cost. They are the first to incorporate the thresholds of weight ternarization into a closed-form expression using truncated Gaussian approximation, which can be optimized through back-propagation together with network's other parameters through the end-to-end training. With both the first and last layer ternarized, the experiments on the ImageNet classification task show that their ternarized ResNet-18/34/50 only has ∼3.9/2.52/2.16% accuracy degradation in comparison to the full-precision counterparts.



---

