# Two-step quantization for low-bit neural networks

## Summary

Summary: The paper proposes a Two-Step Quantization (TSQ) framework for training lower-bit neural networks which consists of code learning and transformation functions. It uses a sparse quantization method for code learning and non-linear least square regression with low-bit constraints for the second step. The proposed method outperforms the state-of-the-art on CIFAR-10 and ILSVRC-12 datasets with a drop in accuracy of only 0.5 points compared to full-precision on 2-bit activation and ternary weight quantization of AlexNet.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose a simple yet effective Two-Step Quantization (TSQ) framework for training extremely-low-bit neural networks with high accuracy. The framework decomposes the network quantization problem into two steps: code learning and transformation function learning based on the learned codes. The proposed sparse quantization method for code learning and the non-linear least square regression problem with low-bit constraints for the second step make the optimization problem easier to solve. Extensive experiments on CIFAR-10 and ILSVRC-12 datasets show that the proposed TSQ outperforms the state-of-the-art by a large margin, with the accuracy of our TSQ dropping only about 0.5 points compared with the full-precision counterpart for 2-bit activation and ternary weight quantization of AlexNet.



---

