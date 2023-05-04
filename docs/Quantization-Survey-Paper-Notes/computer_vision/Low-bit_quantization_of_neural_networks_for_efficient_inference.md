# Low-bit quantization of neural networks for efficient inference

## Summary

<Summary: The paper proposes a method for low-bit precision computation through neural network quantization by using MMSE for weights and activations. The approach can perform 4 bits INT4 quantization for pre-trained models on limited hardware resources, yielding state of the art results with minimal task accuracy loss.>


## Target Task

computer vision

## Content

<Abstract:>
In this research paper, the authors propose a method for performing low-bit precision computations via neural network quantization, allowing for more efficient inference on limited hardware resources. The proposed approach formalizes the linear quantization task as a Minimum Mean Squared Error (MMSE) problem for both weights and activations, enabling low-bit precision inference without full network retraining. Specifically, the authors focus on 4 bits integer (INT4) quantization for deployment of pretrained models on limited hardware resources. Multiple experiments on various network architectures showed that the suggested method yields state of the art results with minimal loss of task accuracy.



---

