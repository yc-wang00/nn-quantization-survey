# Tbn: Convolutional neural network with ternary inputs and binary weights

## Summary

Summary: The paper proposes a Ternary-Binary Network (TBN) to provide an efficient approximation to standard CNNs. TBN replaces the arithmetical operations in standard CNNs with efficient XOR, AND and bitcount operations, and provides an optimal tradeoff between memory, efficiency and performance. TBN demonstrates its consistent effectiveness when applied to various CNN architectures on multiple datasets of different scales, and provides ∼32× memory savings and 40× faster convolutional operations. Meanwhile, TBN can outperform XNOR-Network by up to 5.5% (top-1 accuracy) on the ImageNet classification task, and up to 4.4% (mAP score) on the PASCAL VOC object detection task.


## Target Task

computer vision

## Content

<Abstract: Despite the remarkable success of Convolutional Neural Networks (CNNs) on generalized visual tasks, high computational and memory costs restrict their comprehensive applications on consumer electronics (e.g., portable or smart wearable devices). Recent advancements in binarized networks have demonstrated progress on reducing computational and memory costs, however, they suffer from significant performance degradation comparing to their full-precision counterparts. Thus, a highly-economical yet effective CNN that is authentically applicable to consumer electronics is at urgent need. In this work, we propose a Ternary-Binary Network (TBN), which provides an efficient approximation to standard CNNs. Based on an accelerated ternary-binary matrix multiplication, TBN replaces the arithmetical operations in standard CNNs with efficient XOR, AND and bitcount operations, and thus provides an optimal tradeoff between memory, efficiency and performance. TBN demonstrates its consistent effectiveness when applied to various CNN architectures (e.g., AlexNet and ResNet) on multiple datasets of different scales, and provides ∼32× memory savings and 40× faster convolutional operations. Meanwhile, TBN can outperform XNOR-Network by up to 5.5% (top-1 accuracy) on the ImageNet classification task, and up to 4.4% (mAP score) on the PASCAL VOC object detection task.>



---

