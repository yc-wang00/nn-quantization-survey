# QTI submission to DCASE 2021: Residual normalization for device-imbalanced acoustic scene classification with efficient design

## Summary

<Summary: >The paper discusses the design of an audio scene classification system named Residual Normalization under the constraints of model complexity, with four proposed methods. These methods include Residual Normalization, BC-ResNet-Mod, spectrogram-to-spectrogram translation, and model compression schemes, thereby achieving an average test accuracy of 76.3% in TAU Urban Acoustic Scenes 2020 Mobile dataset containing 315k parameters. The accuracy remained stable at 75.3% even after the model was compressed to 61.0KB.


## Target Task

speech recognition

## Content

<Abstract: > This technical report describes the details of our TASK1A submission of the DCASE2021 challenge. The goal of the task is to design an audio scene classification system for device-imbalanced datasets under the constraints of model complexity. This report introduces four methods to achieve the goal. First, we propose Residual Normalization, a novel feature normalization method that uses instance normalization with a shortcut path to discard unnecessary device-specific information without losing useful information for classification. Second, we design an efficient architecture, BC-ResNet-Mod, a modified version of the baseline architecture with a limited receptive field. Third, we exploit spectrogram-to-spectrogram translation from one to multiple devices to augment training data. Finally, we utilize three model compression schemes: pruning, quantization, and knowledge distillation to reduce model complexity. The proposed system achieves an average test accuracy of 76.3% in TAU Urban Acoustic Scenes 2020 Mobile, development dataset with 315k parameters, and average test accuracy of 75.3% after compression to 61.0KB of non-zero parameters.



---

