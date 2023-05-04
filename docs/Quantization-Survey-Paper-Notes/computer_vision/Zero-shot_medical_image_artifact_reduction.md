# Zero-shot medical image artifact reduction

## Summary

<Summary: > This paper introduces a "Zero-Shot" medical image Artifact Reduction (ZSAR) framework, which leverages the power of deep learning but without pre-trained networks or clean image reference. ZSAR uses the low internal visual entropy of an image and trains a lightweight image-specific artifact reduction network to reduce artifacts in medical imaging, such as CT and MRI, better than state-of-the-art both qualitatively and quantitatively, while using shorter execution time. This is the first deep learning framework introduced for reducing artifacts in medical imaging without using a priori training set, which has wide-ranging clinical adoption.


## Target Task

computer vision

## Content

<Abstract: > Medical images may contain various types of artifacts with different patterns and mixtures, which depend on many factors such as scan setting, machine condition, patients’ characteristics, surrounding environment, etc. However, existing deep learning based artifact reduction methods are restricted by their training set with specific predetermined artifact type and pattern. As such, they have limited clinical adoption. In this paper, we introduce a “Zero-Shot” medical image Artifact Reduction (ZSAR) framework, which leverages the power of deep learning but without using general pre-trained networks or any clean image reference. Specifically, we utilize the low internal visual entropy of an image and train a lightweight image-specific artifact reduction network to reduce artifacts in an image at test-time. We use Computed Tomography (CT) and Magnetic Resonance Imaging (MRI) as vehicles to show that ZSAR can reduce artifacts better than state-of-the-art both qualitatively and quantitatively, while using shorter execution time. To the best of our knowledge, this is the first deep learning framework that reduces artifacts in medical images without using a priori training set.



---

