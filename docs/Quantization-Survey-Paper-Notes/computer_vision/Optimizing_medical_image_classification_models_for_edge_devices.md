# Optimizing medical image classification models for edge devices

## Summary

Summary: This paper investigates the use of model quantization and GPU-acceleration to improve the efficiency of machine learning algorithms for medical diagnostics on edge devices. Quantization techniques were employed and tested, which resulted in a 2-4x reduction in model size and small decreases in mean AUC-ROC score of 0.0%-0.9%. Integer quantization was found to improve inference latency by up to 57% on ARM architectures, but significant latency increases were observed on x86 processors. The use of GPU acceleration improved inference latency, but kernel launch overhead outweighed the benefits. Overall, optimization of diagnostic models has the potential to increase their usefulness in low-resource environments, but improvements are dependent on the context and architecture of the devices being used.


## Target Task

computer vision

## Content

<Abstract: Machine learning algorithms for medical diagnostics often require resource-intensive environments to run, such as expensive cloud servers or high-end GPUs, making these models impractical for use in the field. We investigate the use of model quantization and GPU-acceleration for chest X-ray classification on edge devices. We employ 3 types of quantization (dynamic range, float-16, and full int8) which we tested on models trained on the Chest-XRay14 Dataset. We achieved a 2-4x reduction in model size, offset by small decreases in the mean AUC-ROC score of 0.0%-0.9%. On ARM architectures, integer quantization was shown to improve inference latency by up to 57%. However, we also observed significant increases in latency on x86 processors. GPU acceleration also improved inference latency, but this was outweighed by kernel launch overhead. We show that optimization of diagnostic models has the potential to expand their utility to day-to-day devices used by patients and healthcare workers; however, these improvements are context- and architecture-dependent and should be tested on the relevant devices before deployment in low-resource environments.>



---

