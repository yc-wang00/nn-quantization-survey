# Scalable image retrieval by sparse product quantization

## Summary

Summary: The paper proposes a new approach called Sparse Product Quantization (SPQ) to encode high-dimensional feature vectors into sparse representation for Fast Approximate Nearest Neighbor (ANN) search technique for high-dimensional feature indexing and retrieval. The proposed SPQ technique is able to compress data and obtain state-of-the-art results for ANN search on four public image datasets, validating the efficacy of the proposed method.


## Target Task

computer vision

## Content

<Abstract:>
Fast Approximate Nearest Neighbor (ANN) search technique for high-dimensional feature indexing and retrieval is the crux of large-scale image retrieval. A recent promising technique is Product Quantization, which attempts to index high-dimensional image features by decomposing the feature space into a Cartesian product of low dimensional subspaces and quantizing each of them separately. In this paper, we propose a novel approach called Sparse Product Quantization (SPQ) to encoding the high-dimensional feature vectors into sparse representation. We optimize the sparse representations of the feature vectors by minimizing their quantization errors, making the resulting representation essentially close to the original data in practice. Experiments show that the proposed SPQ technique is not only able to compress data but also an effective encoding technique. We obtain state-of-the-art results for ANN search on four public image datasets, and the promising results of content-based image retrieval further validate the efficacy of our proposed method.



---

