# Learning low-precision neural networks without straight-through estimator (ste)

## Summary

<Summary: > This paper proposes a method called alpha-blending (AB) for quantizing neural networks to low precision using stochastic gradient descent (SGD) that replaces the quantized weight in the loss function with an affine combination of the quantized weight and the corresponding full-precision weight and gradually increases the non-trainable scalar coefficient from 0 to 1 during training, which results in improved top-1 accuracy compared to the Straight-Through Estimator (STE) based quantization technique.


## Target Task

computer vision

## Content

<Abstract: > The Straight-Through Estimator (STE) technique, which is commonly used for propagating gradients through the quantization function, is not fully understood theoretically. This paper proposes an alternative methodology called alpha-blending (AB) that quantizes neural networks to low precision using stochastic gradient descent (SGD). The AB method replaces the quantized weight in the loss function with an affine combination of the quantized weight and the corresponding full-precision weight with a non-trainable scalar coefficient. During training, this coefficient is gradually increased from 0 to 1, and the model is progressively converted from full-precision to low precision. The evaluation of the AB method shows improved top-1 accuracy compared to the results of STE based quantization.



---

