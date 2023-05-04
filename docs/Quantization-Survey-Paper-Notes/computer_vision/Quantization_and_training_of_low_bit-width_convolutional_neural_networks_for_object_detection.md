# Quantization and training of low bit-width convolutional neural networks for object detection

## Summary

<Summary: >The paper presents LBW-Net, an optimization-based method for training low bit-width CNNs, that quantizes weights to zero or powers of two by minimizing the Euclidean distance between full-precision and quantized weights during backpropagation. Compared to full-precision CNNs, LBW-Net offers advantages such as memory savings, energy efficiency, and faster deployment, with nearly lossless performance in object detection tasks and better performance in some real-world visual scenarios. Results from experiments on the PASCAL VOC dataset show more than 4 times faster deployment with 6-bit LBW-Net compared to its 32-bit floating-point counterpart.


## Target Task

computer vision

## Content

<Abstract: >We present LBW-Net, an eﬃcient optimization based method for quantization and training of the low bit-width convolutional neural networks (CNNs). Speciﬁcally, we quantize the weights to zero or powers of two by minimizing the Euclidean distance between full-precision weights and quantized weights during backpropagation. LBW-Net has several desirable advantages over full-precision CNNs, including considerable memory savings, energy eﬃciency, and faster deployment. Our experiments on PASCAL VOC dataset show that compared with its 32-bit ﬂoating-point counterpart, the performance of the 6-bit LBW-Net is nearly lossless in the object detection tasks, and can even do better in some real world visual scenes, while empirically enjoying more than 4 faster deployment.



---

