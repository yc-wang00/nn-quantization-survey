# Post-training quantization for vision transformer

## Summary

<Summary: > The paper presents a post-training quantization algorithm that reduces memory storage and computational costs of vision transformers. The quantization task is optimized for low-bit quantization intervals for weights and inputs, with a ranking loss introduced to preserve the functionality of the attention mechanism. The proposed method outperforms state-of-the-art post-training quantization algorithms and is verified on several benchmark models and datasets.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we present an effective post-training quantization algorithm for reducing the memory storage and computational costs of vision transformers. Basically, the quantization task can be regarded as finding the optimal low-bit quantization intervals for weights and inputs, respectively. To preserve the functionality of the attention mechanism, we introduce a ranking loss into the conventional quantization objective that aims to keep the relative order of the self-attention results after quantization. The effectiveness of the proposed method is verified on several benchmark models and datasets, which outperforms the state-of-the-art post-training quantization algorithms.



---

