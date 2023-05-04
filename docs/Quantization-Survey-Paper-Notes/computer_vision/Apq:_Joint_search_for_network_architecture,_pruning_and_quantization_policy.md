# Apq: Joint search for network architecture, pruning and quantization policy

## Summary

Summary: The paper presents APQ, a design methodology for efficient deep learning deployment. They optimize the neural network architecture, pruning policy, and quantization policy jointly. To deal with the larger design space, they train a quantization-aware accuracy predictor that is fed to the evolutionary search to select the best fit. They propose a predictor-transfer technique to get the quantization-aware predictor to reduce the quantization data collection time.


## Target Task

computer vision

## Content

<Abstract: >
We present APQ, a novel design methodology for efficient deep learning deployment. Unlike previous methods that separately optimize the neural network architecture, pruning policy, and quantization policy, we design to optimize them in a joint manner. To deal with the larger design space it brings, we devise to train a quantization-aware accuracy predictor that is fed to the evolutionary search to select the best fit. Since directly training such a predictor requires time-consuming quantization data collection, we propose to use predictor-transfer technique to get the quantization-aware predictor: we first generate a large dataset of AN architecture, ImageNet accuracy pair by sampling a pretrained unified once-for-all network and doing direct evaluation; then we use these data to train an accuracy predictor without quantization, followed by transferring its weights to train the quantization-aware predictor, which largely reduces the quantization data collection time.



---

