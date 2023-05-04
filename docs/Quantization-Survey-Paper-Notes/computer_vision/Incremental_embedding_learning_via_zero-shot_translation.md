# Incremental embedding learning via zero-shot translation

## Summary

Summary: The paper proposes the use of an incremental learning method called ZSTCI to solve catastrophic forgetting in embedding networks for tasks such as face recognition and zero-shot learning. ZSTCI uses zero-shot translation to accurately estimate the semantic gap between two adjacent tasks. Experimental results on CUB-200-2011 and CIFAR100 datasets show the effectiveness of the proposed method.


## Target Task

computer vision

## Content

<Abstract: >Modern deep learning methods have achieved great success
in machine learning and computer vision fields by learning a set of pre-defined datasets. However, when these methods are applied to the real-world scenarios, the trained model quickly forgets the knowledge of old tasks due to the learning of new tasks, which is known as catastrophic forgetting. In this paper, the authors propose an incremental learning method called zero-shot translation class-incremental method (ZSTCI) to tackle the catastrophic forgetting problem in embedding networks, which are used in tasks such as image retrieval, face recognition, and zero-shot learning. ZSTCI leverages zero-shot translation to estimate the semantic gap between the embedding spaces of two adjacent tasks accurately. The authors conduct experiments on CUB-200-2011 and CIFAR100 datasets and prove the effectiveness of their method.



---

