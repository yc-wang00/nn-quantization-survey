# Q-rater: Non-convex optimization for post-training uniform quantization

## Summary

<Summary: >The paper proposes a new post-training uniform quantization technique, which considers non-convexity and optimizes hyper-parameters using the task loss. This approach shows higher model accuracy, especially for low-bit quantization, in extensive experiments using different models.


## Target Task

computer vision

## Content

<Abstract: >Various post-training uniform quantization methods have usually been studied based on convex optimization. In this paper, we propose a new post-training uniform quantization technique considering non-convexity. We empirically show that hyper-parameters for clipping and rounding of weights and activations can be explored by monitoring task loss. Then, an optimally searched set of hyper-parameters is frozen to proceed to the next layer such that an incremental non-convex optimization is enabled for post-training quantization. Throughout extensive experimental results using various models, our proposed technique presents higher model accuracy, especially for a low-bit quantization.



---

