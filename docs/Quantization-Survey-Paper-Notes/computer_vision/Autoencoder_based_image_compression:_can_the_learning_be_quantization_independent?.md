# Autoencoder based image compression: can the learning be quantization independent?

## Summary

<Summary: >This paper proposes the use of a unique learned transform for image compression, rather than learning one transform per rate-distortion point, which saves training time. The approach involves joint learning of the transform and quantization. The paper investigates if compression is affected at test time when quantization step sizes are different from those in the training stage. The work was supported by the French Defense Procurement Agency.


## Target Task

computer vision

## Content

<Abstract: >This paper explores the problem of learning transforms for image compression via autoencoders. The authors show that comparable performances can be obtained with a unique learned transform, rather than learning one transform per rate-distortion point at a given quantization step size. The different rate-distortion points are then reached by varying the quantization step size at test time, which saves a lot of training time. The paper proposes an approach where the transform and the quantization are learned jointly and investigates whether, at test time, the compression falls apart when the coefficients obtained with the learned transform are quantized using quantization step sizes which differ from those in the training stage. This work has been supported by the French Defense Procurement Agency (DGA).



---

