# Domain adaptation for memory-efficient dense retrieval

## Summary

Summary: The paper proposes a modification to the training procedure of binary embedding models such as BPR and JPQ, which enables their adaptation to any corpus without requiring labeled data. The proposed method, called GPL, improves the nDCG@10 metric across the BEIR benchmark by up to 19.3 and 11.6 points compared to BPR and JPQ while maintaining 32x memory efficiency.


## Target Task

nlp

## Content

<Abstract: >Dense retrievers encode documents into fixed dimensional embeddings. Recently, binary embedding models like BPR and JPQ have been proposed which train the model to produce binary document vectors, reducing the index 32x or more, achieving an improvement in nDCG@10 across the BEIR benchmark. However, these models can perform significantly worse than baselines once there is a domain-shift involved. In this paper, the authors propose a modification to the training procedure of BPR and JPQ and combine it with a corpus specific generative procedure which enables the adaptation of BPR and JPQ to any corpus without requiring labeled training data. Their domain adapted strategy known as GPL is model agnostic, achieving an improvement by up to 19.3 and 11.6 points in nDCG@10 across the BEIR benchmark in comparison to BPR and JPQ while maintaining its 32x memory efficiency.



---

