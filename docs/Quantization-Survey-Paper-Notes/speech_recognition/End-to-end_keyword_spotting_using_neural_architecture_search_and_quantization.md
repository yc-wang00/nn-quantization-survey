# End-to-end keyword spotting using neural architecture search and quantization

## Summary

Summary: This paper proposes a neural architecture search method to optimize convolutional neural networks for keyword spotting on raw audio waveforms in low-resource environments. They explore methods of quantization for reducing memory footprint and achieve a highly efficient KWS model with high accuracy using fixed and trained bit-width quantization.


## Target Task

speech recognition

## Content

<Abstract: > This paper introduces a differentiable neural architecture search (NAS) method for optimizing the structure of convolutional neural networks (CNNs) for keyword spotting (KWS) on raw audio waveforms in resource-constrained environments. We conduct experiments on the Google speech commands dataset, comparing our approach to mel-frequency cepstral coefficient (MFCC)-based systems. We also investigate different methods of quantization for reducing memory footprint, including fixed and trained bit-width quantization. We obtain a highly efficient KWS model with an accuracy of 95.55% using 75.7k parameters and 13.6M operations with NAS alone. The same model achieves a test accuracy of 93.76% using trained bit-width quantization while using only 2.91 bits per activation and 2.51 bits per weight on average.



---

