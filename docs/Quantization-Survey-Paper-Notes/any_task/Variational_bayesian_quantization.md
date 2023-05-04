# Variational bayesian quantization

## Summary

Summary: The paper proposes an algorithm for quantizing continuous latent representations in trained models. This algorithm is applicable to deep probabilistic models such as VAEs and enables both data and model compression. Unlike current end-to-end neural compression methods, this approach allows for a variable rate-distortion trade-off using a single trained model. This algorithm is based on arithmetic coding and uses adaptive quantization accuracy based on estimates of posterior uncertainty. Therefore, it allows for "plug-and-play" compression without the need for fixed quantization schemes.


## Target Task

any task

## Content

<Abstract: We propose a novel algorithm for quantizing continuous latent representations in trained models. Our approach applies to deep probabilistic models, such as variational autoencoders (VAEs), and enables both data and model compression. Unlike current end-to-end neural compression methods that cater the model to a fixed quantization scheme, our algorithm separates model design and training from quantization. Consequently, our algorithm enables “plug-and-play” compression with variable rate-distortion trade-off, using a single trained model. Our algorithm can be seen as a novel extension of arithmetic coding to the continuous domain and uses adaptive quantization accuracy based on estimates of posterior uncertainty.>



---

