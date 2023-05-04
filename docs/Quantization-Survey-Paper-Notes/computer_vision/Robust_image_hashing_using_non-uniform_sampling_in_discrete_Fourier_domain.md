# Robust image hashing using non-uniform sampling in discrete Fourier domain

## Summary

Summary: The paper proposes a robust image hashing method in discrete Fourier domain for image authentication and retrieval. The method involves using image resizing, total variation based filtering, rotation projection, and non-uniform sampling to extract the robust frequency feature from the secondary image after discrete Fourier transform. The intermediate sampling feature vectors are then scrambled and quantized to produce the resulting binary hash securely. The method is shown to have satisfactory robustness against perceptual content-preserving manipulations and low probability for collision of the hashes of distinct images.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes a robust image hashing method in discrete Fourier domain that can be applied in such fields as image authentication and retrieval. In the pre-processing stage, image resizing and total variation based filtering are first used to regularize the input image. Then the secondary image is obtained by the rotation projection, and the robust frequency feature is extracted from the secondary image after discrete Fourier transform. More sampling points are chosen from the low- and middle-frequency component to represent the salient content of the image effectively, which is achieved by the non-uniform sampling. Finally, the intermediate sampling feature vectors are scrambled and quantized to produce the resulting binary hash securely. The security of the method depends entirely on the secret key. Experiments are conducted to show that the present method has satisfactory robustness against perceptual content-preserving manipulations and has also very low probability for collision of the hashes of distinct images.



---

