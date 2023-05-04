# Analysis of quantized models

## Summary

Summary: The paper discusses the use of weight and gradient quantization for deep neural networks to increase storage and fast inference on low-end devices. Theoretical analysis and empirical experiments confirm that quantized networks can speed up training while having comparable performance as full-precision networks. Clipping the gradient before quantization allows for the use of fewer bits for gradient quantization.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks are usually huge, which significantly limits the deployment on low-end devices. In recent years, many weight-quantized models have been proposed. They have small storage and fast inference, but training can still be time-consuming. This can be improved with distributed learning. To reduce the high communication cost due to worker-server synchronization, recently gradient quantization has also been proposed to train deep networks with full-precision weights. In this paper, we theoretically study how the combination of both weight and gradient quantization affects convergence. We show that (i) weight-quantized models converge to an error related to the weight quantization resolution and weight dimension; (ii) quantizing gradients slows convergence by a factor related to the gradient quantization resolution and dimension; and (iii) clipping the gradient before quantization renders this factor dimension-free, thus allowing the use of fewer bits for gradient quantization. Empirical experiments confirm the theoretical convergence results, and demonstrate that quantized networks can speed up training and have comparable performance as full-precision networks.



---

