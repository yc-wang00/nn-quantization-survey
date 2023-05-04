# Streamlined deployment for quantized neural networks

## Summary

<Summary: > 
This paper discusses the challenges of running Deep Neural Network (DNN) models on devices with limited computational capability and how Quantized Neural Networks (QNNs) can solve these challenges. The paper provides a streamlining flow to convert all QNN inference operations to integer ones and techniques based on processing one bit position at a time to show how QNNs can be efficiently deployed using common bitwise operations. The paper demonstrates the potential of QNNs on mobile CPUs with microbenchmarks and on a quantized AlexNet, which is 3.5× faster than an optimized 8-bit baseline.


## Target Task

computer vision

## Content

<Abstract: >Running Deep Neural Network (DNN) models on devices with limited computational capability is a challenge due to large compute and memory requirements. Quantized Neural Networks (QNNs) have emerged as a potential solution to this problem, promising to offer most of the DNN accuracy benefits with much lower computational cost. In this work, we first describe a streamlining flow to convert all QNN inference operations to integer ones. Afterwards, we provide techniques based on processing one bit position at a time (bit-serial) to show how QNNs can be efficiently deployed using common bitwise operations. We demonstrate the potential of QNNs on mobile CPUs with microbenchmarks and on a quantized AlexNet, which is 3.5×faster than an optimized 8-bit baseline. Our bit-serial matrix multiplication library is available on GitHub.



---

