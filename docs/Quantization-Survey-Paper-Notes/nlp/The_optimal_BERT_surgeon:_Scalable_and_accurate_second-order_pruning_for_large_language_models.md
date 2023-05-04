# The optimal BERT surgeon: Scalable and accurate second-order pruning for large language models

## Summary

<Summary: >The paper introduces optimal BERT Surgeon (oBERT), an efficient and accurate pruning method, for sparse BERT models. This method allows for pruning blocks of weights, and is effective in both pre-training and fine-tuning stages of language tasks. The paper also investigates compounding compression approaches for obtaining highly accurate models for deployment on edge devices. The proposed method improves the state-of-the-art sparse BERT models in terms of model size, inference speed and task accuracy. The code is available on Github.


## Target Task

nlp

## Content

<Abstract: > In this paper, we introduce the Optimal BERT Surgeon (oBERT), an efficient and accurate pruning method based on approximate second-order information, for the sparsification of BERT models. We extend existing work on second-order pruning by allowing for pruning blocks of weights, and show that oBERT yields state-of-the-art results for compression in both stages of language tasks: pre-training and fine-tuning. Furthermore, we investigate compounding compression approaches to obtain highly compressed but accurate models for deployment on edge devices. We obtain significant improvements over the current state-of-the-art sparse BERT models with respect to all metrics: model size, inference speed and task accuracy. Our code, fully integrated with Transformers and SparseML, is freely available at https://github.com/neuralmagic/sparseml/tree/main/research/optimal_BERT_surgeon_oBERT.



---

