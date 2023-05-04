# Unsupervised texture classification using vector quantization and deterministic relaxation neural network

## Summary

Summary: The paper proposes using a neural network architecture to classify textured images in an unsupervised manner that incorporates image-specific constraints. The model includes feature quantization, partition, and competition processes using Gabor filters arranged as a set of wavelet bases. A derived energy function represented by the neural network with a set of label constraints for each pixel in the image is used to adjust the state of the network and vector quantizer until a stable state is reached, which provides a classification of the textured image.


## Target Task

computer vision

## Content

<Abstract: >This paper describes a neural network architecture used to classify textured images in an unsupervised manner, while incorporating image-specific constraints. The features are extracted using a set of 2D Gabor filters arranged as a set of wavelet bases. The classification model includes feature quantization, partition, and competition processes, and is determined by a derived energy function represented by a neural network, using a set of label constraints for each pixel in the image. The state of the network and vector quantizer are adjusted using a deterministic relaxation procedure until a stable state is reached, and the final equilibrium state of the vector quantizer gives a classification of the textured image.



---

