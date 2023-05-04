# Metaicl: Learning to learn in context

## Summary

Summary: The paper presents a Meta-training framework for few-shot learning called MetaICL. In this approach, a pretrained language model is fine-tuned to perform in-context learning on a large set of training tasks which enable the model to more effectively learn a new task at test time. The experiment shows that MetaICL outperforms several baselines for NLP tasks including in-context learning without meta-training and multi-task learning followed by zero-shot transfer.


## Target Task

nlp

## Content

<Abstract:>
We introduce MetaICL (Meta-training for In-Context Learning), a new meta-training framework for few-shot learning where a pretrained language model is tuned to do in-context learning on a large set of training tasks. This meta-training enables the model to more effectively learn a new task in context at test time, by simply conditioning on a few training examples with no parameter updates or task-specific templates. We experiment on a large, diverse collection of tasks consisting of 142 NLP datasets including classification, question answering, natural language inference, paraphrase detection, and more, across seven different meta-training/target splits. MetaICL outperforms a range of baselines including in-context learning without meta-training and multi-task learning followed by zero-shot transfer.



---

