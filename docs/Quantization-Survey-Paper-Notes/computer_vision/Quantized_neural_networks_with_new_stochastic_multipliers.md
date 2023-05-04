# Quantized neural networks with new stochastic multipliers

## Summary

<Summary: > The authors introduce a new stochastic multiplier with shifted unary code adders (SUC-Adder) for quantized neural networks. They use quantization and stochastic computing to reduce hardware cost. They retrain fully trained neural networks to obtain quantized weights and implement a stochastic matrix multiplication using the SUC-Adder component. The stochastic design reduces energy consumption by about 10x compared to binary implementation while maintaining slightly higher recognition error rates.


## Target Task

computer vision

## Content

<Abstract:> In this paper, the authors propose a new stochastic multiplier with shifted unary code adders (SUC-Adder) for quantized neural networks. They combine the technologies of quantization and stochastic computing in neural networks to reduce hardware cost further. They first retrain a fully trained neural network with the back-propagation algorithm in order to obtain neural networks with quantized weights. Then, according to the quantized weights, a stochastic matrix multiplication is implemented with the SUC-Adder component. Experimental results indicate that their stochastic design achieves about 10x energy reduction compared to its counterpart binary implementation while maintaining slightly higher recognition error rates than the binary implementation.



---

