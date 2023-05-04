# Differentiable model compression via pseudo quantization noise

## Summary

<Summary: >The paper proposes DiffQ, a differentiable method for model compression for quantizing model parameters. The method involves adding independent pseudo quantization noise to model parameters during training to approximate the effect of a quantization operator. DiffQ optimizes the number of bits used per individual weight or groups of weights, given a single hyper-parameter balancing between the quantized model size and accuracy in end-to-end training. The authors demonstrate that their method is competitive with STE based quantization techniques on several benchmarks and architectures for image classification, language modeling, and audio source separation.


## Target Task

computer vision

## Content

<Abstract: >We propose DiffQa diﬀerentiable method for model compression for quantizing model parameters without gradient approximations. The method adds independent pseudo quantization noise to model parameters during training to approximate the eﬀect of a quantization operator. DiffQis diﬀerentiable both with respect to the unquantized weights and the number of bits used. Given a single hyper-parameter balancingbetweenthequantizedmodelsizeandaccuracy, DiffQoptimizesthenumberofbits used per individual weight or groups of weights, in end-to-end training. The authors experimentally verify that their method is competitive with STE based quantization techniques on several benchmarks and architectures for image classification, language modeling, and audio source separation. For instance, on the ImageNet dataset, DiffQcompresses a 12 layers transformer-based model by more than a factor of 8, with a loss of 0.3% in model accuracy.



---

