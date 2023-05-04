# Zero-shot knowledge distillation from a decision-based black-box model

## Summary

<Summary: > The paper proposes a new concept of decision-based black-box (DB3) knowledge distillation, which enables training a compact network (student) using a black-box teacher that only returns classes. The approach computes a sample's robustness against other classes and constructs a soft label for each training sample to train the student via standard knowledge distillation. The proposed method is evaluated on various networks and datasets, and the results demonstrate their effectiveness, even in scenarios where the training data is not accessible.


## Target Task

computer vision

## Content

<Abstract: >Knowledge distillation is a popular approach for deep neural network acceleration, with a pre-trained high-capacity network (teacher) used to train a compact network (student) by mimicking the softmax output. However, accessing the white-box teacher's parameters and training samples is not always feasible due to privacy or storage costs. Here, we propose the concept of decision-based black-box (DB3) knowledge distillation that trains a student using a black-box teacher that only returns classes. Our approach computes a sample's robustness against other classes and constructs a soft label for each training sample to train the student via standard KD. In more challenging scenarios when the training data is not accessible, we generate pseudo samples and construct soft labels using decision boundaries of the DB3 teacher. We evaluate our approach on various networks and datasets, and results demonstrate their effectiveness.



---

