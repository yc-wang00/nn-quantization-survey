# A Generalized Zero-Shot Quantization of Deep Convolutional Neural Networks via Learned Weights Statistics

## Summary

Summary: The paper discusses the limitations of existing zero-shot quantization methods that rely on batch normalization parameters and proposes a generalized zero-shot quantization (GZSQ) framework that does not require original data or BN layer statistics. The authors use data distillation to estimate enriched data for range calibration of activations and demonstrate improved classification accuracy (33%) for various models with and without BN layers. The proposed model is also applicable for unnormalized deep neural networks.


## Target Task

computer vision

## Content

<Abstract: >Quantizing floating-point weights and activations of deep convolutional neural networks to fixed-point representation yields reduced memory footprints and inference time. Recently, zero-shot quantization methods that do not require original unlabelled training samples of a given task have been proposed. However, most of these methods heavily rely on the learned batch normalization (BN) parameters to infer the range of activations for quantization, and their performance severely degrades when presented with a network that does not accommodate BN layers. In this work, we propose a generalized zero-shot quantization (GZSQ) framework that neither requires original data nor relies on BN layer statistics. We have utilized the data distillation approach and leverage only the pre-trained weights of the model to estimate enriched data for the range calibration of activations. Our scheme has significantly outperformed existing zero-shot works, an improvement of 33% in classification accuracy for MobileNetV2 and several other models with and without BN layers, for a variety of tasks. We have also demonstrated the efficacy of the proposed work across multiple open-source quantization frameworks. Importantly, our work is the first attempt towards the post-training zero-shot quantization of futuristic unnormalized deep neural networks.



---

