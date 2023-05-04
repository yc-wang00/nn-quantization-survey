# All you need is a few shifts: Designing efficient convolutional neural networks for image classification

## Summary

<Summary: >The paper proposes the use of shift operations to create efficient convolutional neural networks. They introduce a new basic component called Sparse Shift Layer (SSL). A shift operation penalty is introduced during optimization, and a quantization-aware shift learning method is proposed. The paper shows that only a few shift operations are enough for spatial communication. Lastly, an improved network architecture named FE-Net is introduced that achieves 75.0% top-1 accuracy on ImageNet with only 563M M-Adds.


## Target Task

computer vision

## Content

<Abstract:> Shift operation is introduced in this paper to construct efficient convolutional neural networks. A new and novel basic component named Sparse Shift Layer (SSL) is added to the architecture in which the basic block is only composed of 1x1 convolutional layers with only a few shift operations applied to the intermediate feature maps. They introduce a shift operation penalty during optimization and further propose a quantization-aware shift learning method to make the idea feasible. It is shown that only a few shift operations are sufficient to provide spatial information communication. Furthermore, an improved network architecture named FE-Net is introduced which can achieve 75.0% top-1 accuracy on ImageNet with only 563M M-Adds.



---

