# Towards zero-shot knowledge distillation for natural language processing

## Summary

<Summary: >The paper presents the first work on Zero-Shot Knowledge Distillation for NLP, which uses out of domain data and adversarial training to transfer knowledge from a teacher model to a student model without access to the teacher's training data. The proposed method achieved between 75% and 92% of the teacher's classification score while compressing the model 30 times on six tasks from the GLUE benchmark.


## Target Task

nlp

## Content

<Abstract: >Knowledge Distillation (KD) is a common knowledge transfer algorithm used for model compression across a variety of deep learning based natural language processing (NLP) solutions. In its regular manifestations, KD requires access to the teacher’s training data for knowledge transfer to the student network. However, privacy concerns, data regulations and proprietary reasons may prevent access to such data. We present, to the best of our knowledge, the first work on Zero-Shot Knowledge Distillation for NLP, where the student learns from the much larger teacher without any task specific data. Our solution combines out of domain data and adversarial training to learn the teacher’s output distribution. We investigate six tasks from the GLUE benchmark and demonstrate that we can achieve between 75% and 92% of the teacher’s classification score (accuracy or F1) while compressing the model 30 times.



---

