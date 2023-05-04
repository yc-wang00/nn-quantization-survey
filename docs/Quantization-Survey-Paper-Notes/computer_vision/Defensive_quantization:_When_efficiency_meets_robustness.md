# Defensive quantization: When efficiency meets robustness

## Summary

Summary: This paper discusses a new approach called Defensive Quantization that optimizes both the efficiency and robustness of deep learning models. This method controls the Lipschitz constant of the network during quantization to defend against adversarial attacks by making sure that the adversarial noise's magnitude remains non-expansive during inference. This results in superior robustness compared to full-precision models while maintaining the same level of hardware efficiency as vanilla quantization approaches.


## Target Task

computer vision

## Content

<Abstract: >Neural network quantization is becoming an industry standard to efficiently deploy deep learning models on hardware platforms. However, conventional quantization approaches are vulnerable to adversarial attacks, and the inferior robustness comes from the error amplification effect. This paper proposes a novel Defensive Quantization method to jointly optimize the efficiency and robustness of deep learning models. The method controls the Lipschitz constant of the network during quantization such that the adversarial noise's magnitude remains non-expansive during inference. The new quantization method effectively defends neural networks against adversarial examples and even achieves superior robustness than their full-precision counterparts, while maintaining the same hardware efficiency as vanilla quantization approaches.



---

