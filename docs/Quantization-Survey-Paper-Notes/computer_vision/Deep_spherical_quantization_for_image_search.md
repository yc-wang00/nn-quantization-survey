# Deep spherical quantization for image search

## Summary

Summary: The authors propose a method called Deep Spherical Quantization (DSQ) to generate compact binary codes for efficient image search by learning a mapping to transform high-dimensional images into a low-dimensional discriminative space and quantizing the transformed data points using multi-codebook quantization. The technique includes a supervised quantization technique for vectors on the unit hypersphere and an extension for enforcing sparsity on the codebooks. The experiments show that DSQ outperforms state-of-the-art image retrieval methods on three benchmarks.


## Target Task

computer vision

## Content

<Abstract: >
In this paper, the authors propose a novel method called Deep Spherical Quantization (DSQ) to generate supervised and compact binary codes for efficient image search. The approach simultaneously learns a mapping to transform high-dimensional images into a low-dimensional discriminative space and quantizes the transformed data points using multi-codebook quantization. The network is forced to L2normalize the features to eliminate the negative effect of norm variance on codebook learning. The resulting vectors are then quantized using a new supervised quantization technique specifically designed for points lying on a unit hypersphere. The authors also introduce an easy-to-implement extension of the technique that enforces sparsity on the codebooks. The experiments demonstrate that DSQ and its sparse variant can generate semantically separable compact binary codes outperforming many state-of-the-art image retrieval methods on three benchmarks.



---

