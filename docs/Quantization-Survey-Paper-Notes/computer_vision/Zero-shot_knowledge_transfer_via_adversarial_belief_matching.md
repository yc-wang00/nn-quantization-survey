# Zero-shot knowledge transfer via adversarial belief matching

## Summary

<Summary: >The paper proposes a method to train a smaller student network to match the predictions of a larger teacher network without using any data or metadata. The method involves training an adversarial generator to find images on which the student poorly matches the teacher, which are then used to train the student. The resulting student approximates its teacher on simple datasets, and outperforms the state-of-the-art for few-shot distillation on CIFAR10 with 100 images per class. The paper also proposes a metric to quantify the degree of belief matching, and observes a higher match between the zero-shot student and teacher compared to a student distilled with real data.


## Target Task

computer vision

## Content

<Abstract: >Performing knowledge transfer from a large teacher network to a smaller student is a popular task in modern deep learning applications. However, due to growing dataset sizes and stricter privacy regulations, it is increasingly common not to have access to the data that was used to train the teacher. We propose a novel method which trains a student to match the predictions of its teacher without using any data or metadata. We achieve this by training an adversarial generator to search for images on which the student poorly matches the teacher, and then using them to train the student. Our resulting student closely approximates its teacher for simple datasets like SVHN, and on CIFAR10 we improve on the state-of-the-art for few-shot distillation (with 100 images per class), despite using no data. Finally, we also propose a metric to quantify the degree of belief matching between teacher and student in the vicinity of decision boundaries, and observe a significantly higher match between our zero-shot student and the teacher, than between a student distilled with real data and the teacher.



---

