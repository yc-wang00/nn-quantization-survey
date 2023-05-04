# Training quantized neural networks to global optimality via semidefinite programming

## Summary

<Summary: >This article discusses the importance of neural network weights quantization due to its impact on energy efficiency, inference time and hardware deployment. The paper introduces a convex optimization approach to train polynomial activation-based quantized neural networks, which can be solved to global optimality in polynomial time using semidefinite relaxations. The article also presents examples to illustrate the effectiveness of this method, and describes prior research on compression and quantization of neural networks for hardware implementation.


## Target Task

computer vision

## Content

<Abstract: >Neural networks have been successful in various areas of machine learning. The quantization of neural network weights has become important due to its impact on the energy efficiency, inference time and deployment on hardware. Although post-training quantization is well-studied, training optimal quantized neural networks involves combinatorial non-convex optimization problems which are usually intractable. This research introduces a convex optimization approach to train quantized neural networks with polynomial activations. By leveraging hidden convexity in two-layer neural networks from recent literature, semidefinite lifting, and Grothendieck's identity, the authors show that certain quantized neural network problems can be solved to global optimality in polynomial time using tight semidefinite relaxations. Numerical examples are presented to illustrate the effectiveness of their method. Prior work on compression and quantization of neural networks for hardware implementations is also discussed.>



---

