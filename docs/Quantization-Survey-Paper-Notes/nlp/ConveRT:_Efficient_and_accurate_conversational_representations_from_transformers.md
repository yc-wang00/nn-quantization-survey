# ConveRT: Efficient and accurate conversational representations from transformers

## Summary

<Summary: > This paper introduces ConveRT, a pre-training framework for conversational AI applications that is computationally efficient and fast to train. It uses quantization and subword-level parameterization to build a lightweight and energy-efficient model with state-of-the-art performance in response selection tasks. Furthermore, the use of extended dialog history as context yields further performance gains. It can also be transferred to the intent classification task with strong results. ConveRT trains substantially faster than standard sentence encoders or previous state-of-the-art dual encoders, making it more portable and scalable for conversational AI applications.


## Target Task

nlp

## Content

<Abstract: > General-purpose pretrained sentence encoders such as BERT are not ideal for real-world conversational AI applications; they are computationally heavy, slow, and expensive to train. We propose ConveRT (Conversational Representations from Transformers), a pre-training framework for conversational tasks satisfying all the following requirements: it is effective, affordable, and quick to train. We pretrain using a retrieval-based response selection task, effectively leveraging quantization and subword-level parameterization in the dual encoder to build a lightweight memory- and energy-efficient model. We show that ConveRT achieves state-of-the-art performance across widely established response selection tasks. We also demonstrate that the use of extended dialog history as context yields further performance gains. Finally, we show that pretrained representations from the proposed encoder can be transferred to the intent classification task, yielding strong results across three diverse datasets. ConveRT trains substantially faster than standard sentence encoders or previous state-of-the-art dual encoders. With its reduced size and superior performance, we believe this model promises wider portability and scalability for Conversational AI applications.



---

