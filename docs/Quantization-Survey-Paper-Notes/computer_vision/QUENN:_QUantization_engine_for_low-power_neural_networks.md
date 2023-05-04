# QUENN: QUantization engine for low-power neural networks

## Summary

Summary: The paper presents a framework and engine, LPDNN and QUENN respectively, for deploying deep neural networks on embedded devices using quantization techniques. It demonstrates the potential of k-means clustering with Gaussian quantization for achieving better performance than linear quantizers in Imagenet, with significant savings in weights' storage and run-time memory accesses and minimal drop in top5 accuracy.


## Target Task

computer vision

## Content

<Abstract:>
Deep Learning is becoming increasingly popular on edge devices opening new frontiers for distributed Artificial Intelligence (AI). However, deep neural networks demand significant computational resources that can be reduced by methods such as reduced-precision arithmetic and coarsely quantized numerical representations. LPDNN is a framework that enables the optimized deployment of Deep Neural Networks on heterogeneous embedded devices, and QUENN is a quantization engine that is integrated in LPDNN. The quantization engine depends on a fine-grained workflow that enables a Neural Network Design Exploration and a sensitivity analysis of each layer for quantization. The paper demonstrates the engine with a case study on Alexnet and VGG16 for three different techniques for direct quantization: standard fixed-point, dynamic fixed-point and k-means clustering, and demonstrates the potential of the latter. Gaussian quantizer with k-means clustering can achieve better performance than linear quantizers. The potential of the technique is demonstrated with Imagenet, where over 55.64% saving for weights’ storage and 69.17% for run-time memory accesses with less than 1% drop in top5 accuracy is achieved without retraining.



---

