# Prune once for all: Sparse pre-trained language models

## Summary

<Summary: >This paper describes a method for sparse pre-training Transformer-based language models. The proposed method trains the sparse models using weight pruning and model distillation. The authors demonstrate that these compressed models transfer their knowledge to various natural language tasks as well as maintaining their sparsity pattern. Moreover, the paper shows how to further compress the sparse models' weights using quantization-aware training to achieve the best compression-to-accuracy ratio for BERT-Base, BERT-Large, and DistilBERT models.


## Target Task

nlp

## Content

<Abstract: >Transformer-based language models, such as BERT and RoBERTa, have become the standard approach for natural language processing. However, their large size requires high computational and memory resources, making their deployment challenging. Model compression methods, such as weight pruning, have been proposed to address this issue. In this paper, we present a method for training sparse pre-trained Transformer-based language models using weight pruning and model distillation. Our method demonstrates that these sparse pre-trained models can be used for a wide range of downstream natural language tasks while maintaining their sparsity pattern. The compressed sparse pre-trained models we trained transfer their knowledge to five different natural language tasks with minimal accuracy loss. Furthermore, we show how to further compress the sparse models' weights to 8-bit precision using quantization-aware training, achieving the best compression-to-accuracy ratio for BERT-Base, BERT-Large, and DistilBERT.



---

