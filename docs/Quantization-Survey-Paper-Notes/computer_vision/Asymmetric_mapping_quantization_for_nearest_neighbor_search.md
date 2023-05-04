# Asymmetric mapping quantization for nearest neighbor search

## Summary

Summary: The paper proposes a novel addition-based vector quantization algorithm, Asymmetric Mapping Quantization (AMQ), for performing approximate nearest neighbor (ANN) search. The proposed method maps the query vector and database vector using different mapping functions, solving the problem caused by the norm of the database vector. The paper also proposes Distributed Asymmetric Mapping Quantization (DAMQ) to allow AMQ to work with large datasets by distributed learning. Experiments conducted on approximate nearest neighbor search and image retrieval demonstrate the effectiveness of the proposed methods.


## Target Task

computer vision

## Content

<Abstract: >
Nearest neighbor search is an important problem in computer vision and machine learning. Although hashing methods are traditionally used for approximate nearest neighbor (ANN) search, vector quantization-based methods have recently gained popularity due to their superior accuracy and efficiency. In this paper, a novel addition-based vector quantization algorithm, Asymmetric Mapping Quantization (AMQ), is proposed to perform ANN search. Unlike existing addition-based quantization methods, AMQ maps the query vector and database vector using different mapping functions, transforming the computation of L-2 distance to inner product similarity, and solves the problem caused by the norm of the database vector. The authors also propose Distributed Asymmetric Mapping Quantization (DAMQ) to allow AMQ to work with large datasets by distributed learning. Experiments conducted on approximate nearest neighbor search and image retrieval demonstrate the effectiveness of the proposed methods.



---

