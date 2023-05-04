# Extreme zero-shot learning for extreme text classification

## Summary

Summary: The paper proposes a new pre-training method called MACLR to address the Extreme Zero-Shot XMC problem which requires no supervision and has access only to raw text of instances and labels. The proposed method utilizes self-supervised contrastive losses, Multi-scale Adaptive Clustering, Label Regularization, and self-training with pseudo-positive pairs. The authors show that the proposed method achieves superior performance compared to other baseline methods and fine-tuning the pre-trained encoder on a few-shot subset improves the performance on the Few-Shot XMC setup.


## Target Task

nlp

## Content

<Abstract: >
In this research paper, the authors address the eXtreme Multi-label text Classification (XMC) problem, which involves finding the most relevant labels for a given input text instance from a large label set. They propose a new scenario called Extreme Zero-Shot XMC (EZ-XMC) that requires no supervision and only has access to raw text of instances and labels. To address this problem, they propose a pre-training method called MACLR that utilizes self-supervised contrastive losses and other techniques such as Multi-scale Adaptive Clustering, Label Regularization, and self-training with pseudo-positive pairs. The authors evaluate the proposed method on four public EZ-XMC datasets and show that it achieves superior performance compared to other baseline methods with approximately 5-10% improvement in precision and recall on average. They also show that fine-tuning the pre-trained encoder on a few-shot subset improves the performance on the Few-Shot XMC (FS-XMC) setup.



---

