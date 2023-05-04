# Joint learning of deep retrieval model and product quantization based embedding index

## Summary

<Summary: >The paper presents a novel method called Poeem for embedding index in deep retrieval systems. It unifies the embedding learning and index building steps by utilizing gradient straight-through estimator, warm start strategy, optimal space decomposition and Givens rotation techniques in end-to-end training. The proposed method significantly improves retrieval accuracy and reduces indexing time to nearly zero, according to the experimental results. The approach is open-sourced for reproducibility and comparison purposes.


## Target Task

computer vision

## Content

<Abstract: >Embedding index that enables fast approximate nearest neighbor (ANN) search, serves as an indispensable component for state-of-the-art deep retrieval systems. Traditional approaches, often separating the two steps of embedding learning and index building, incur additional indexing time and decayed retrieval accuracy. In this paper, we propose a novel method called Poeem, which stands for product quantization based embedding index jointly trained with deep retrieval model, to unify the two separate steps within an end-to-end training, by utilizing a few techniques including the gradient straight-through estimator, warm start strategy, optimal space decomposition and Givens rotation. Extensive experimental results show that the proposed method not only improves retrieval accuracy significantly but also reduces the indexing time to almost none. We have open sourced our approach for the sake of comparison and reproducibility.



---

