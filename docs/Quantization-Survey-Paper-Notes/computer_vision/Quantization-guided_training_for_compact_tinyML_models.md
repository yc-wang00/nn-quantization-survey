# Quantization-guided training for compact tinyML models

## Summary

Summary: The paper proposes a method called Quantization Guided Training (QGT) to optimize deep neural network (DNN) training for low-bit-precision targets. The method uses customized regularization to encourage weight values towards a distribution that maximizes accuracy while reducing quantization errors. The proposed method is demonstrated with an 81KB tiny model for person detection down to 2-bit precision, representing a 17.7x size reduction, while maintaining an accuracy drop of only 3% compared to a floating-point baseline.


## Target Task

computer vision

## Content

<Abstract:>
We propose a Quantization Guided Training (QGT) method to optimize DNN training for low-bit-precision targets and achieve compression levels below 8-bit precision. This method uses customized regularization to encourage weight values towards a distribution that maximizes accuracy while reducing quantization errors. QGT is able to identify compression bottlenecks and can be used for state-of-the-art model architectures on vision datasets. The proposed method is demonstrated with an 81KB tiny model for person detection down to 2-bit precision, representing a 17.7x size reduction, while maintaining an accuracy drop of only 3% compared to a floating-point baseline.



---

