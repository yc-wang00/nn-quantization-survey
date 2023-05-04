# Bitpruning: Learning bitlengths for aggressive and accurate quantization

## Summary

<Summary: >The paper proposes a training method for neural network quantization that minimizes the inference bit-length while maintaining accuracy. The method introduces a regularizer that penalizes large bit-length representations throughout the architecture. The average per layer bit-length on AlexNet, ResNet18, and MobileNet V2 is 4.13, 3.76, and 4.36 bits respectively, staying within 2.0%, 0.5%, and 0.5% of the base TOP-1 accuracy. The proposed method helps achieve state-of-the-art accuracy using low-bit-length integers quantization, resulting in energy and execution time benefits.


## Target Task

computer vision

## Content

<Abstract: >Neural networks have achieved state-of-the-art accuracy using low-bitlength integer quantization, yielding execution time and energy benefits. However, determining the minimum bitlength required for a desired accuracy remains an open question. This paper proposes a training method that minimizes inference bitlength while maintaining accuracy, by introducing a regularizer that penalizes large bitlength representations throughout the architecture. The method produces an average per layer bitlength of 4.13, 3.76 and 4.36 bits on AlexNet, ResNet18 and MobileNet V2 respectively, remaining within 2.0%, 0.5% and 0.5% of the base TOP-1 accuracy.



---

