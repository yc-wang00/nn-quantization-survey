# Zerogen: Efficient zero-shot learning via dataset generation

## Summary

<Summary: >This paper proposes a method called ZER0GEN for zero-shot learning, which involves generating a dataset from scratch using pre-trained language models, and then training a task model using this dataset. Experiments on several NLP tasks demonstrate the effectiveness of the proposed method.


## Target Task

nlp

## Content

<Abstract: >There is a growing interest in dataset generation recently due to the superior generative capacity of large pre-trained language models (PLMs). In this paper, we study a flexible and efficient zero-short learning method, ZER0GEN. Given a zero-shot task, we first generate a dataset from scratch using PLMs in an unsupervised manner. Then, we train a tiny task model (e.g., LSTM) under the supervision of the synthesized dataset. Experiments and analysis on different NLP tasks, namely, text classification, question answering, and natural language inference, show the effectiveness of ZER0GEN.



---

