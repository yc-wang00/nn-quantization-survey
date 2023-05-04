# Jointly optimizing query encoder and product quantization to improve retrieval performance

## Summary

<Summary: > The paper proposes a new method, Joint optimization of query encoding and Product Quantization (JPQ), to overcome the efficiency problem in Dense Retrieval (DR) with vector compression methods such as Product Quantization (PQ). The evaluation shows that JPQ significantly outperforms popular vector compression methods with 30x compression on index size, bringing 10x speedup on CPU and 2x speedup on GPU in query latency.


## Target Task

information retrieval

## Content

<Abstract: >Recently, Information Retrieval community has witnessed fast-paced advances in Dense Retrieval (DR), which performs first-stage retrieval with embedding-based search. To overcome the efficiency problem in practical web search scenarios, vector compression methods have been adopted. One of the most popular methods is Product Quantization (PQ). However, vector compression methods incur severely decayed retrieval performance due to the separation between encoding and compression. To tackle this problem, the authors present JPQ, which stands for Joint optimization of query encoding and Product Quantization. They evaluate JPQ on two publicly available retrieval benchmarks and show that it significantly outperforms popular vector compression methods. Compared with previous DR models that use brute-force search, JPQ almost matches the best retrieval performance with 30x compression on index size. The compressed index further brings 10x speedup on CPU and 2x speedup on GPU in query latency.



---

