# Composite quantization

## Summary

Summary: The paper proposes a composite quantization framework for approximating nearest neighbor search using a short code composed of indices of elements selected from different dictionaries. The approach called near-orthogonal composite quantization guarantees search efficiency through a near-orthogonality constraint, reducing the cost of distance computation. The proposed approach achieves state-of-the-art performance in approximating nearest neighbor search in terms of the Euclidean distance.


## Target Task

computer vision

## Content

<Abstract: > This paper introduces a composite quantization framework to convert vectors to compact codes, with the goal of approximating nearest neighbor search. The idea is to approximate a vector using the composition of M elements each selected from a different dictionary, and to represent this vector by a short code composed of the indices of the selected elements. The resulting approach is called near-orthogonal composite quantization. A near-orthogonality constraint is introduced to make search efficiency guaranteed, reducing the cost of distance computation from O(D) to O(M) through a distance table lookup scheme. The equivalence between near-orthogonal composite quantization and minimizing an upper bound of a function is theoretically justified. The proposed approach achieves state-of-the-art performances in approximate nearest neighbor search in terms of the Euclidean distance.



---

