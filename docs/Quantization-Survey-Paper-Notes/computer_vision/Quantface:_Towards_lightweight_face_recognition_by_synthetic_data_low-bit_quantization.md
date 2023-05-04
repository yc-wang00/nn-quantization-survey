# Quantface: Towards lightweight face recognition by synthetic data low-bit quantization

## Summary

<Summary: > The paper proposes a solution, QuantFace, based on low-bit precision format model quantization, to reduce computational costs of existing over-parameterized deep learning face recognition models. The solution reduces the model size up to 5x without designing a specific architecture or accessing real training datasets. Privacy-friendly synthetic face data is used to the quantization process to avoid privacy concerns and make the training codes publicly available. The evaluation experiment shows the reduction in computational costs while maintaining the verification performance of full-precision models.


## Target Task

computer vision

## Content

<Abstract: >Deep learning-based face recognition models rely on over-parameterized DNN with high computational costs. However, deploying such large models on devices constrained by computational requirements is challenging. Previous solutions proposed to design special compact architectures and train them from scratch using real training data. In this paper, we present the QuantFace solution based on low-bit precision format model quantization. QuantFace reduces the required computational cost of existing face recognition models without the need for designing a particular architecture or accessing real training data. Through evaluation experiments on seven benchmarks, we demonstrate that QuantFace can successfully reduce the model size up to 5x while maintaining, to a large degree, the verification performance of the full-precision model without accessing real training datasets. The solution introduces privacy-friendly synthetic face data to the quantization process to mitigate potential privacy concerns and issues related to the accessibility to real training data. The training codes are publicly available.



---

