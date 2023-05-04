# Stochastic precision ensemble: self-knowledge distillation for quantized deep neural networks

## Summary

<Summary:>

The paper introduces a new training scheme for quantized deep neural networks (QDNNs) called Stochastic Precision Ensemble Training (SPEQ). The proposed scheme uses knowledge distillation (KD) with a teacher network formed by sharing model parameters of the student network. The soft labels of the teacher network are obtained through random bit-precision assignments made stochastically at each layer's forward-pass computation. The student model then learns with these soft labels to reduce activation quantization noise, and cosine similarity loss is employed instead of KL-divergence during KD training. The proposed method outperforms existing quantization training approaches for various tasks such as image classification, question-answering, and transfer learning without the need for cumbersome teacher networks.


## Target Task

computer vision

## Content

Abstract: The quantization of deep neural networks (QDNNs) has been actively studied for deployment in edge devices. Recent studies employ the knowledge distillation (KD) method to improve the performance of quantized networks. In this study, we propose stochastic precision ensemble training for QDNNs (SPEQ). SPEQ is a knowledge distillation training scheme; however, the teacher is formed by sharing the model parameters of the student network. We obtain the soft labels of the teacher by randomly changing the bit precision of the activation stochastically at each layer of the forward-pass computation. The student model is trained with these soft labels to reduce the activation quantization noise. The cosine similarity loss is employed, instead of the KL-divergence, for KD training. As the teacher model changes continuously by random bit-precision assignment, it exploits the effect of stochastic ensemble KD. SPEQ outperforms the existing quantization training methods in various tasks, such as image classification, question-answering, and transfer learning without the need for cumbersome teacher networks.



---

