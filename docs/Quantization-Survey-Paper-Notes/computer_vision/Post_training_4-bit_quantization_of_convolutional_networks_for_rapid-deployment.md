# Post training 4-bit quantization of convolutional networks for rapid-deployment

## Summary

Summary: This paper presents a practical 4-bit post-training quantization approach for convolutional neural networks, that does not require training of quantized model or full dataset. The approach proposes three complementary methods for minimizing quantization errors at the tensor level, and achieves high accuracy just a few percent less than state-of-the-art baseline across various convolutional models.


## Target Task

computer vision

## Content

<Abstract: >Convolutional neural networks can be computationally expensive, requiring significant memory and storage resources. Neural network quantization can reduce the amount of intermediate results, but the process often requires the full dataset and time-consuming fine-tuning to recover accuracy lost after quantization. This paper presents a practical 4-bit post-training quantization approach that does not involve training the quantized model or the availability of the full dataset. The paper proposes three complementary methods for minimizing quantization errors at the tensor level, two of which obtain a closed-form analytical solution. The approach achieves accuracy that is just a few percent less than the state-of-the-art baseline across a range of convolutional models.



---

