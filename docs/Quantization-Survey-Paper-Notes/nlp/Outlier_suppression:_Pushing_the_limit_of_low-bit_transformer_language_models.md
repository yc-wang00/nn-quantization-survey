# Outlier suppression: Pushing the limit of low-bit transformer language models

## Summary

Summary: This paper discusses the issue of memory and computation costs in large natural language processing models and how quantization can help solve this problem. The paper proposes an outlier suppression framework that includes two components: Gamma Migration and Token-Wise Clipping, which suppress the outliers effectively, push the 6-bit post-training BERT quantization to the full-precision level, and contribute to a more quantization-friendly model without adding any extra burden.


## Target Task

nlp

## Content

<Abstract: >Transformer architecture has become a fundamental element of natural language processing models. With the growth of large NLP models, the memory and computation costs have become a major hindrance to their efficient deployment on resource-limited devices. Transformer quantization has attracted widespread research interest to solve this issue. Recent studies show that structured outliers are the critical bottleneck for quantization performance. However, the proposed methods increase computation overhead and leave the outliers in place. This paper delves into the inherent inducement and importance of the outliers and proposes an outlier suppression framework, including two components: Gamma Migration and Token-Wise Clipping. These components contribute to a more quantization-friendly model without any extra burden, suppress the outliers effectively, and push the 6-bit post-training BERT quantization to the full-precision level.



---

