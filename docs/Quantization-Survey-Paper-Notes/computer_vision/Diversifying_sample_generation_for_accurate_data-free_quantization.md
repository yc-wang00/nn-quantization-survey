# Diversifying sample generation for accurate data-free quantization

## Summary

Summary: The Diverse Sample Generation (DSG) scheme is proposed to mitigate the performance drop in quantized neural network models due to homogenized synthetic data created for calibration. It slackens the alignment of feature statistics in BN layer to relax the constraint at the distribution level, and designs a layerwise enhancement to reinforce specific layers for different data samples. It consistently improves various network architectures and quantization methods, especially when quantized to lower bits. The synthetic data calibrated models perform close to those with real data and even outperform them on W4A4.


## Target Task

computer vision

## Content

<Abstract:>
Quantization is a prevalent approach for compressing and accelerating neural networks, and data-free quantization has been studied as a promising solution. However, the synthetic data created for calibration suffers from homogenization at both distribution and sample levels, leading to a performance drop in quantized models. To mitigate this issue, the Diverse Sample Generation (DSG) scheme is proposed, which slackens the alignment of feature statistics in the BN layer to relax the constraint at the distribution level and designs a layerwise enhancement to reinforce specific layers for different data samples. The DSG scheme consistently improves various network architectures and quantization methods for large-scale image classification tasks, especially when quantized to lower bits. Moreover, models calibrated with synthetic data perform close to those calibrated with real data and even outperform them on W4A4.



---

