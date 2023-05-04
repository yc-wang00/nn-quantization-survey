# Deep neural network quantization via layer-wise optimization using limited training data

## Summary

Summary: The paper presents a layer-wise quantization method for deep neural networks, using a discrete optimization problem and ADMM to provide an efficient closed-form solution. The method is effective in preserving the performance of the original network post-quantization, and is tested with 1% of CIFAR10 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract:>
The paper proposes a layer-wise quantization method for deep neural networks that only requires limited training data. The method formulates parameters quantization for each layer as a discrete optimization problem and solves it using Alternative Direction Method of Multipliers (ADMM), which gives an efficient closed-form solution. The proposed method is able to preserve the performance of the original network after quantization. Extensive experiments on benchmark deep models are conducted to demonstrate the effectiveness of our proposed method using 1% of CIFAR10 and ImageNet datasets.



---

