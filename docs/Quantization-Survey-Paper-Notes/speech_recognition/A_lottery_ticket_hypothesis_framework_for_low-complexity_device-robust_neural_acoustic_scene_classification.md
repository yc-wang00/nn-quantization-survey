# A lottery ticket hypothesis framework for low-complexity device-robust neural acoustic scene classification

## Summary

Summary: The paper proposes a new approach to neural model compression named Acoustic Lottery, which compresses an acoustic scene classification model by combining data augmentation, knowledge transfer, pruning, and quantization. This approach achieves superior performance compared to its uncompressed seed model. The proposed system uses a data augmentation process, teach-student learning mechanism, Lottery Ticket Hypothesis based pruning, two-stage fusion technique, and quantization block to deliver a low-complexity model.


## Target Task

speech recognition

## Content

<Abstract: >
We propose a novel neural model compression strategy combining
data augmentation, knowledge transfer, pruning, and quantization
for device-robust acoustic scene classification (ASC). Our model, called Acoustic Lottery, largely compresses an ASC model and achieves superior performance (validation accuracy of 79.4% and Log loss of 0.64) compared to its not compressed seed model. The proposed Acoustic Lottery system consists of a data augmentation process to improve model generalization, a teach-student learning mechanism to transfer knowledge, from a large teacher model to a small student model, a Lottery Ticket Hypothesis based pruning method to deliver a low-complexity model, a two-stage fusion technique to improve model prediction, and finally, a quantization block to deploy a final model.



---

