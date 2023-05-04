# Improving passage retrieval with zero-shot question generation

## Summary

<Summary: >The proposed paper presents a re-ranking method which uses a zero-shot question generation model to improve passage retrieval in open question-answering systems. It is a simple and effective approach that can be applied to any retrieval method and provides rich cross-attention between query and passage. It does not require any domain or task-specific training and provides new state-of-the-art results on full open-domain question answering.


## Target Task

nlp

## Content

<Abstract: >We propose a simple and effective re-ranking method for improving passage retrieval in open question answering. The re-ranker re-scores retrieved passages with a zero-shot question generation model, which uses a pre-trained language model to compute the probability of the input question conditioned on a retrieved passage. This approach can be applied on top of any retrieval method (e.g. neural or keyword-based), does not require any domain- or task-specific training (and therefore is expected to generalize better to data distribution shifts), and provides rich cross-attention between query and passage (i.e. it must explain every token in the question). When evaluated on a number of open-domain retrieval datasets, our re-ranker improves strong unsupervised retrieval models by 6%-18% absolute and strong supervised models by up to 12% in terms of top-20 passage retrieval accuracy. We also obtain new state-of-the-art results on full open-domain question answering by simply adding the new re-ranker to existing models with no further changes.



---

