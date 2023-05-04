# QUANOS: adversarial noise sensitivity driven hybrid quantization of neural networks

## Summary

Summary: The authors propose QUANOS, a framework that performs layer-specific hybrid quantization based on Adversarial Noise Sensitivity (ANS) to enhance the adversarial robustness of Deep Neural Networks (DNNs). They identify a novel noise stability metric for DNNs, ANS, which allows for a principled way of determining the optimal bit-width per layer that incurs adversarial robustness as well as energy-efficiency with minimal loss in accuracy. QUANOS outperforms homogeneously quantized 8-bit precision baseline in terms of adversarial robustness while yielding improved compression and energy savings at iso-accuracy.


## Target Task

computer vision

## Content

<Abstract:>
Deep Neural Networks (DNNs) have been shown to be vulnerable to adversarial attacks, which limits their deployment in real-world applications. In this paper, the authors propose QUANOS, a framework that performs layer-specific hybrid quantization based on Adversarial Noise Sensitivity (ANS). They identify a novel noise stability metric for DNNs, ANS, which allows for a principled way of determining the optimal bit-width per layer that incurs adversarial robustness as well as energy-efficiency with minimal loss in accuracy. QUANOS outperforms homogeneously quantized 8-bit precision baseline in terms of adversarial robustness, while yielding improved compression and energy savings at iso-accuracy. At iso-compression rate, QUANOS yields significantly higher adversarial robustness than similar sized baseline against strong white-box attacks. Combining QUANOS with state-of-the-art defense methods outperforms the state-of-the-art in robustness against very strong attacks.



---

