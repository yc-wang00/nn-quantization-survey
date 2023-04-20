# Training quantized neural networks to global optimality via semidefinite programming

## Summary

Summary: This paper introduces a convex optimization strategy to train quantized neural networks with polynomial activations. The current post-training quantization is well-studied but training optimal quantized neural networks involves combinatorial non-convex optimization problems which appear intractable. The proposed method has shown that certain quantized neural network problems can be solved to global optimality using tight semidefinite relaxations in all relevant parameters provably in polynomial time. The effectiveness of the method is demonstrated with numerical examples.


## Target Task

Target: any task.

## Content

<Abstract: >Neural networks (NNs) have been extremely successful across many tasks in machine learning. Quantization of NN weights has become an important topic due to its impact on their energy efficiency, inference time and deployment on hardware. Although post-training quantization is well-studied, training optimal quantized NNs involves combinatorial non-convex optimization problems which appear intractable. In this work, we introduce a convex optimization strategy to train quantized NNs with polynomial activations. Our method leverages hidden convexity in two-layer neural networks from the recent literature, semidefinite lifting, and Grothendieck’s identity. Surprisingly, we show that certain quantized NN problems can be solved to global optimality provably in polynomial time in all relevant parameters via tight semidefinite relaxations. We present numerical examples to illustrate the effectiveness of our method.



---

