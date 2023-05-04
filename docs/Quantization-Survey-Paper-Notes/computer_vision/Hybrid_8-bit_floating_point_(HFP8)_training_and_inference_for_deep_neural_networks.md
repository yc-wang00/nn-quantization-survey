# Hybrid 8-bit floating point (HFP8) training and inference for deep neural networks

## Summary

Summary: 
The paper proposes a hybrid FP8 (HFP8) format and DNN end-to-end distributed training procedure that successfully trains deep learning models across a spectrum of applications without accuracy degradation by reducing the numerical precision of data and computation. The proposed techniques enable a new generation of 8-bit hardware for building and deploying neural network models without losing accuracy by simply fine-tuning batch normalization statistics.


## Target Task

computer vision

## Content

<Abstract: >
Reducing the numerical precision of data and computation is extremely effective
in accelerating deep learning training workloads. Towards this end, 8-bit ﬂoating
point representations (FP8) were recently proposed for DNN training. However,
its applicability was only demonstrated on a few selected models and signiﬁcant
degradation is observed when popular networks such as MobileNet and Trans-
former are trained using FP8. This degradation is due to the inherent precision
requirement difference in the forward and backward passes of DNN training. Using
theoretical insights, we propose a hybrid FP8 (HFP8) format and DNN end-to-end
distributed training procedure. We demonstrate, using HFP8, the successful train-
ing of deep learning models across a whole spectrum of applications including
Image Classiﬁcation, Object Detection, Language and Speech without accuracy
degradation. Finally, we demonstrate that, by using the new 8 bit format, we can
directly quantize a pre-trained model down to 8-bits without losing accuracy by
simply ﬁne-tuning batch normalization statistics. These novel techniques enable a
new generations of 8-bit hardware that are robust for building and deploying neural
network models.



---

