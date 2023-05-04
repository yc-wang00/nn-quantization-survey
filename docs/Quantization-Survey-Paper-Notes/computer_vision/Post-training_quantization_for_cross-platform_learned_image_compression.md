# Post-training quantization for cross-platform learned image compression

## Summary

Summary: The paper proposes a solution to the non-deterministic calculation problem in image compression techniques with post-training quantization. The method maintains superior rate-distortion performance and allows for consistent cross-platform inference, making the application of learned image compression more promising.


## Target Task

computer vision

## Content

<Abstract:> It has been observed that learned image compression techniques are more efficient than conventional image coding techniques and are practical in industrial applications. However, a significant issue that needs to be addressed is the non-deterministic calculation that leads to cross-platform inconsistency in probability prediction, causing decoding to fail. In this paper, we propose a solution to this problem by introducing post-training quantization, which makes model inference integer-arithmetic-only. Our method is much simpler than existing approaches and still maintains the superior rate-distortion performance of learned image compression. We further refine the discretization of the entropy parameters and extend deterministic inference to fit Gaussian mixture models. With our proposed method, the current state-of-the-art image compression models can infer in a cross-platform consistent manner, which makes the further application of learned image compression more promising.



---

