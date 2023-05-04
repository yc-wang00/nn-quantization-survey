# Post-training quantization is all you need to perform cross-platform learned image compression

## Summary

<Summary: >The paper proposes post-training quantization to solve the cross-platform inconsistencies in learned image compression. The proposed method simplifies the process yet provides a superior rate-distortion performance. The method allows the state-of-the-art compression models to infer cross-platform consistently, promising the development and practice of learned image compression.


## Target Task

computer vision

## Content

<Abstract: >It has been witnessed that learned image compression has outperformed conventional image coding techniques and tends to be practical in industrial applications. One of the most critical issues that need to be considered is the non-deterministic calculation, which makes the probability prediction cross-platform inconsistent and frustrates successful decoding. We propose to solve this problem by introducing well-developed post-training quantization and making the model inference integer-arithmetic-only, which is much simpler than presently existing training and fine-tuning based approaches yet still keeps the superior rate-distortion performance of learned image compression. With our proposed methods, the current state-of-the-art image compression models can infer in a cross-platform consistent manner, which makes the further development and practice of learned image compression more promising.



---

