# Incremental network quantization: Towards lossless cnns with low-precision weights

## Summary

Summary: This paper proposes a novel method called incremental network quantization (INQ) to convert pre-trained full-precision CNNs into low-precision versions with weights constrained to powers of two or zero. Iterative weight partition, group-wise quantization and re-training are used to incrementally enhance accuracy, resulting in similar or better accuracy than baseline models with 4-bit, 3-bit and 2-bit ternary weights. The method shows promise for deep CNNs on mobile or embedded devices.


## Target Task

computer vision

## Content

<Abstract:>
This paper proposes incremental network quantization (INQ), a novel method for efficiently converting pre-trained full-precision convolutional neural networks (CNNs) into low-precision versions with weights constrained to powers of two or zero. Unlike existing methods that suffer a noticeable loss in accuracy, INQ employs three interdependent operations: weight partition, group-wise quantization, and re-training. A well-proven measure is used to divide pre-trained CNN model weights into two groups, where the first group forms a low-precision base and the second compensates for accuracy loss through quantization and is re-trained. These operations are iteratively repeated on the latest re-trained group until all the weights are converted into low-precision ones, incrementally enhancing accuracy. Extensive experiments testify to the efficacy of the proposed method on the ImageNet classification task using popular deep CNN architectures such as AlexNet, VGG-16, GoogleNet, and ResNets. Quantized models with 4-bit, 3-bit, and 2-bit ternary weights achieve similar or better accuracy than their 32-bit floating-point baseline. Moreover, the combination of network pruning and INQ further enhances performance. The proposed method sheds new light on how to apply deep CNNs to mobile or embedded devices.



---

