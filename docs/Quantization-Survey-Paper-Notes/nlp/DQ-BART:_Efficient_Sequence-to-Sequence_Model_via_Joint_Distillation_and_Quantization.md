# DQ-BART: Efficient Sequence-to-Sequence Model via Joint Distillation and Quantization

## Summary

<Summary: > This paper proposes a method to jointly distill and quantize large-scale pre-trained sequence-to-sequence models, such as BART and T5, to alleviate memory requirements and high latency in resource-constrained scenarios. The proposed method transfers knowledge from full-precision teacher models to quantized and distilled low-precision student models. Empirical analyses show that this method achieves a 16.5x model footprint compression ratio with little performance drop, relative to full-precision models, on multiple summarization and QA datasets. This study pushes the limit of compression ratio to 27.7x and demonstrates the performance-efficiency trade-off for generative tasks using pre-trained models. This is the first work that aims to effectively distill and quantize sequence-to-sequence pre-trained models for language generation tasks.


## Target Task

nlp

## Content

<Abstract: >Large-scale pre-trained sequence-to-sequence models like BART and T5 achieve state-of-the-art performance on many generative NLP tasks. However, such models pose a great challenge in resource-constrained scenarios owing to their large memory requirements and high latency. To alleviate this issue, we propose to jointly distill and quantize the model, where knowledge is transferred from the full-precision teacher model to the quantized and distilled low-precision student model. Empirical analyses show that, despite the challenging nature of generative tasks, we were able to achieve a 16.5x model footprint compression ratio with little performance drop relative to the full-precision counterparts on multiple summarization and QA datasets. We further pushed the limit of compression ratio to 27.7x and presented the performance-efficiency trade-off for generative tasks using pre-trained models. To the best of our knowledge, this is the first work aiming to effectively distill and quantize sequence-to-sequence pretrained models for language generation tasks.



---

