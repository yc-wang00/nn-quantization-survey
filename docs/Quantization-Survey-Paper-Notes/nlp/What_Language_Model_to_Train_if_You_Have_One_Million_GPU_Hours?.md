# What Language Model to Train if You Have One Million GPU Hours?

## Summary

<Summary: >The research aims to find an architecture and training setup that will efficiently and accurately train billion-parameter scale models. The study includes a comparison of different modeling practices and their impact on zero-shot generalization, as well as an analysis of popular pre-training corpora and their impact on zero-shot generalization. The study also examines the performance of a multilingual model and scaling behavior of Transformers in choosing the target model size, shape, and training setup.


## Target Task

nlp

## Content

<Abstract: > The crystallization of modeling methods around the Transformer architecture has been a boon for practitioners. Simple, well-motivated architectural variations can transfer across tasks and scale, increasing the impact of modeling research. However, with the emergence of state-of-the-art 100B+ parameters models, large language models are increasingly expensive to accurately design and train. Our goal is to identify an architecture and training setup that makes the best use of our 1,000,000 A100-GPU-hours budget. Specifically, we perform an ablation study at the billion-parameter scale comparing different modeling practices and their impact on zero-shot generalization. In addition, we study the impact of various popular pre-training corpora on zero-shot generalization. We also study the performance of a multilingual model and how it compares to the English-only one. Finally, we consider the scaling behavior of Transformers to choose the target model size, shape, and training setup.



---

