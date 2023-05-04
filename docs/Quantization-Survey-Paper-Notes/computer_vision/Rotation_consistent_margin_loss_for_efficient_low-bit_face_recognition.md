# Rotation consistent margin loss for efficient low-bit face recognition

## Summary

<Summary: >The paper proposes a rotation consistent margin loss to improve low-bit quantization in face recognition through the disentanglement of quantization errors in angular space into individual and class errors. Instead of minimizing the entire quantization error, only the individual error is minimized to increase feature discriminative power. The proposed loss is found to be superior in low-bit quantization on benchmark datasets such as MegaFace Challenge, Youtube Faces (YTF), Labeled Face in the Wild (LFW) and IJB-C.


## Target Task

computer vision

## Content

<Abstract: > In this paper, we propose a rotation consistent margin (RCM) loss to address the low-bit quantization problem in face recognition (FR) under the open-set protocol. We redefine quantization errors (QEs) in angular space and disentangle them into class error and individual error, which correspond to inter-class separability and intra-class compactness, respectively. Instead of eliminating the entire QEs, we minimize the individual error with RCM loss, which improves feature discriminative power. Extensive experiments demonstrate the superiority of our proposed loss in low-bit FR quantization tasks on popular benchmark datasets such as MegaFace Challenge, Youtube Faces (YTF), Labeled Face in the Wild (LFW) and IJB-C.



---

