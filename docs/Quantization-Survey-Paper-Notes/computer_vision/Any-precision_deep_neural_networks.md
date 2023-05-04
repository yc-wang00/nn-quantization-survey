# Any-precision deep neural networks

## Summary

<Summary: >The paper presents any-precision deep neural networks that are trained with a new method to allow the learned DNNs to be flexible in numerical precision. The same model can be directly set to different bit-widths in runtime, enabling dynamic speed and accuracy trade-offs. The proposed framework achieves this flexibility without any performance degradation and can be applied to multiple vision tasks. This allows flexible deployment of deep learning models in real-world applications.


## Target Task

computer vision

## Content

<Abstract: >We present any-precision deep neural networks (DNNs), which are trained with a new method that allows the learned DNNs to be ﬂexible in numerical precision during inference. The same model in runtime can be ﬂexibly and directly set to different bit-widths, by truncating the least significant bits, to support dynamic speed and accuracy trade-off. When all layers are set to low-bits, we show that the model achieved accuracy comparable to dedicated models trained at the same precision. This nice property facilitates ﬂexible deployment of deep learning models in real-world applications, where in practice trade-offs between model accuracy and runtime efﬁciency are often sought. Previous literature presents solutions to train models at each individual ﬁxed efﬁciency/accuracy trade-off point. But how to produce a model ﬂexible in runtime precision is largely unexplored. When the demand of efﬁciency/accuracy trade-off varies from time to time or even dynamically changes in runtime, it is infeasible to re-train models accordingly, and the storage budget may forbid keeping multiple models. Our proposed framework achieves this ﬂexibility without performance degradation. More importantly, we demonstrate that this achievement is agnostic to model architectures and applicable to multiple vision tasks.



---

