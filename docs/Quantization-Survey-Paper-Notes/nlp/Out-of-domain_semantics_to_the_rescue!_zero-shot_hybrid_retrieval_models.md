# Out-of-domain semantics to the rescue! zero-shot hybrid retrieval models

## Summary

<Summary: > The paper studies the generalization of deep retrieval models over different tasks and domains. While they perform better than lexical models in many retrieval tasks, their performance is significantly weakened when the target domain is very different from the source domain they were trained on. Thus, the paper proposes a framework that combines lexical and deep retrieval models to achieve better and more robust performance. The hybrid model improved by an average of 20.4% relative gain over deep retrieval model and 9.54% over the lexical model in three out-of-domain datasets.


## Target Task

nlp

## Content

<Abstract: > The pre-trained language model ( eg,BERT) based deep retrieval models achieved superior performance over lexical retrieval models (eg,BM25) in many passage retrieval tasks. However, limited work has been done to generalize a deep retrieval model to other tasks and domains. In this work, we carefully select five datasets, including two in-domain datasets and three out-of-domain datasets with different levels of domain shift, and study the generalization of a deep model in a zero-shot setting. Our findings show that the performance of a deep retrieval model is significantly deteriorated when the target domain is very different from the source domain that the model was trained on. On the contrary, lexical models are more robust across domains. We thus propose a simple yet effective framework to integrate lexical and deep retrieval models. Our experiments demonstrate that these two models are complementary, even when the deep model is weaker in the out-of-domain setting. The hybrid model obtains an average of 20.4% relative gain over the deep retrieval model, and an average of 9.54% over the lexical model in three out-of-domain datasets.



---

