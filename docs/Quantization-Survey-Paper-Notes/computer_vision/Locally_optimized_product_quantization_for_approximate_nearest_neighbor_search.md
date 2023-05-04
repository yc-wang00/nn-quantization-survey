# Locally optimized product quantization for approximate nearest neighbor search

## Summary

Summary: The paper presents a vector quantizer that achieves low distortion and fast search for approximate nearest neighbor (ANN) search in high dimensional spaces. It leverages the existing data structure used for non-exhaustive search, optimizes an individual product quantizer (PQ) per cell, and uses it to encode residuals. The optimization is done using a parametric solution, assuming normal distribution, which is quick to train. The method achieves state-of-the-art results on several public datasets, including a billion-scale one, with low space and time overhead.


## Target Task

computer vision

## Content

<Abstract:>
We present a simple vector quantizer that combines low distortion with fast search and apply it to approximate nearest neighbor (ANN) search in high dimensional spaces. Leveraging the very same data structure that is used to provide non-exhaustive search, i.e., inverted lists or a multi-index, the idea is to locally optimize an individual product quantizer (PQ) per cell and use it to encode residuals. Local optimization is over rotation and space decomposition; interestingly, we apply a parametric solution that assumes a normal distribution and is extremely fast to train. With a reasonable space and time overhead that is constant in the data size, we set a new state-of-the-art on several public datasets, including a billion-scale one.



---

