# Knowledge distillation for optimization of quantized deep neural networks

## Summary

<Summary:> This paper explores the optimization of quantized deep neural networks (QDNNs) using knowledge distillation (KD) technique with pre-trained teacher models. The experiments conducted in this study proved that the importance of the softmax distribution produced by the teacher network is more than its performance for effective KD training. Additionally, the paper introduces the Gradual Soft Loss Reducing (GSLR) technique for robust KD based QDNN optimization, which controls the mixing ratio of hard and soft losses during training. Section 2 describes how QDNN can be trained with KD and explains the importance of KD hyperparameters. Section 3 presents the experimental results, and Section 4 concludes the paper.


## Target Task

computer vision

## Content

<Abstract: > Knowledge distillation (KD) technique is used for the optimization of quantized deep neural networks (QDNNs) by utilizing a pre-trained teacher model for training a student network. This paper explores several large floating-point models and quantized ones as the teacher and investigates the effect of hyperparameters for KD. The experiments show that the softmax distribution produced by the teacher network is more important than its performance for effective KD training. The paper proposes the gradual soft loss reducing (GSLR) technique for robust KD based QDNN optimization, which controls the mixing ratio of hard and soft losses during training. Section 2 describes how QDNN can be trained with KD and explains why the hyperparameters of KD are important. Section 3 shows the experimental results and Section 4 concludes the paper.



---

