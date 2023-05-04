# Fine-grained data distribution alignment for post-training quantization

## Summary

Summary: The paper proposes a method called fine-grained data distribution alignment (FDDA) to enhance the performance of post-training quantization using synthetic data introduced by zero-shot quantization with calibration dataset. The method uses batch normalization statistics (BNS) to align the distribution of synthetic data with the original data by considering inter-class separation and intra-class incohesion of BNS. The proposed method significantly improves the performance of post-training quantization, especially when both the first and last layers are quantized to low-bit. The code is available at https://github.com/zysxmu/FDDA.


## Target Task

computer vision

## Content

<Abstract: While post-training quantization receives popularity mostly
due to its evasion in accessing the original complete training dataset, its poor performance also stems from scarce images. To alleviate this limitation, in this paper, we leverage the synthetic data introduced by zero-shot quantization with calibration dataset and propose a fine-grained data distribution alignment (FDDA) method to boost the performance of post-training quantization. The method is based on two important properties of batch normalization statistics (BNS) we observed in deep layers of the trained network, i.e., inter-class separation and intra-class incohesion. To preserve this fine-grained distribution information: 1) We calculate the per-class BNS of the calibration dataset as the BNS centers of each class and propose a BNS-centralized loss to force the synthetic data distributions of different classes to be close to their own centers. 2) We add Gaussian noise into the centers to imitate the incohesion and propose a BNS-distorted loss to force the synthetic data distribution of the same class to be close to the distorted centers. By utilizing these two fine-grained losses, our method manifests the state-of-the-art performance on ImageNet, especially when both the first and last layers are quantized to the low-bit. Code is at https://github.com/zysxmu/FDDA .
Keywords: Batch normalization statistics; Post-training quantization; Synthetic data>



---

