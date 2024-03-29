# Training high-performance and large-scale deep neural networks with full 8-bit integers

## Summary

Summary: This paper proposes a complete quantization framework called "WAGEUBN" to quantize deep neural networks (DNNs) for training and inference using only low bit-width integer data, including weights, activation, gradient, error, update, and batch normalization (BN), with the goal of achieving faster processing speed, decreased memory cost, and higher energy efficiency. The proposed framework has achieved competitive accuracy on ResNet18/34/50 models on the ImageNet dataset, and advances the study of quantization in large-scale DNNs to the full 8-bit INT level, with potential for future efficient portable devices with online learning ability.


## Target Task

computer vision

## Content

Abstract:—Deep neural network (DNN) quantization converting ﬂoating-point (FP) data in the network to integers (INT) is an effective way to shrink the model size for memory saving and simplify the operations for compute acceleration. Recently, researches on DNN quantization develop from inference to training, laying a foundation for the online training on accelerators. However, existing schemes leaving batch normalization (BN) untouched during training are mostly incomplete quantization that still adopt high precision FP in some parts of the data paths. Currently, there is no solution that can use only low bit-width INT data during the whole training process of large-scale DNNs with acceptable accuracy. In this work, through decomposing all the computation steps in DNNs and fusing three special quantization functions to satisfy the different precision requirements, we propose a unified complete quantization framework termed as “WAGEUBN” to quantize DNNs involving all data paths including W (Weights), A (Activation), G (Gradient), E (Error), U (Update), and BN. Moreover, the Momentum optimizer is also quantized to realize a completely quantized framework. Experiments on ResNet18/34/50 models demonstrate that WAGEUBN can achieve competitive accuracy on the ImageNet dataset. For the first time, the study of quantization in large-scale DNNs is advanced to the full 8-bit INT level. In this way, all the operations in the training and inference can be bit-wise operations, pushing towards faster processing speed, decreased memory cost, and higher energy efficiency. Our throughout quantization framework has great potential for future efficient portable devices with online learning ability. 
Keywords: Neural Network Quantization, 8-bit Training, Full Quantization, Online Learning Device



---

