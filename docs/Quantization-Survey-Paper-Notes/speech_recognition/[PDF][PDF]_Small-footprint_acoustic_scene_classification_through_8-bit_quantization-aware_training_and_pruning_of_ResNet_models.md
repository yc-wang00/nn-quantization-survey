# [PDF][PDF] Small-footprint acoustic scene classification through 8-bit quantization-aware training and pruning of ResNet models

## Summary

Summary: This report discusses the IDLab submissions for Task 1a of the DCASE Challenge 2021, focused on creating an acoustic scene classification model of size under 128 KB. Techniques such as ResNet with SE blocks, temporal cropping, time domain mixup, and speed-change augmentation were used. Parameter reduction techniques were utilized, and the model achieved an accuracy of 71.2% on the standard test set of the TAU Urban Acoustic Scenes 2020 Mobile development dataset.


## Target Task

speech recognition

## Content

<Abstract: >
This report describes the IDLab submissions for Task 1a of the DCASE Challenge 2021, focused on constructing an acoustic scene classification model with a size of less than 128 KB. The submitted systems consisted of a ResNet based model enhanced with Squeeze-and-Excitation (SE) blocks trained with temporal cropping, time domain mixup and speed-change augmentation strategies. Parameter reduction techniques were explored, such as weight quantization, grouped convolutions and pruning, as well as prediction score post-processing that directly optimizes the log loss criterion through logistic regression-based calibration. The uncalibrated 8-bit model achieved a log loss of 0.82 and an accuracy of 71.2% on the standard test set of the TAU Urban Acoustic Scenes 2020 Mobile development dataset.



---

