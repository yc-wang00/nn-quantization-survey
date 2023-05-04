# Distilled low rank neural radiance field with quantization for light field compression

## Summary

Summary: The paper proposes a new light field compression technique called QDLR-NeRF, which uses a Neural Radiance Field (NeRF) to learn an implicit scene representation and enable view synthesis. The method reduces model size by learning under a Low Rank (LR) constraint using a Tensor Train (TT) decomposition in an Alternating Direction Method of Multipliers (ADMM) optimization framework and by quantizing the components of the tensor train decomposition. To overcome the optimization challenge, a network distillation operation that separates the LR approximation and the weight quantization in the network training is introduced. The experimental results show that the proposed technique achieves better compression efficiency compared to state-of-the-art methods and allows for high-quality light field view synthesis.


## Target Task

computer vision

## Content

<Abstract: > In this paper, a novel light field compression method called Quantized Distilled Low Rank Neural Radiance Field (QDLR-NeRF) representation is proposed. Unlike other compression methods that encode the set of light field sub-aperture images, this method learns an implicit scene representation in the form of a Neural Radiance Field (NeRF), which also enables view synthesis. The size of the model is reduced by first learning it under a Low Rank (LR) constraint using a Tensor Train (TT) decomposition in an Alternating Direction Method of Multipliers (ADMM) optimization framework. To further reduce the model size, the components of the tensor train decomposition need to be quantized. The optimization of the NeRF model by simultaneously taking the low rank constraint and the rate-constrained weight quantization into consideration is challenging. To deal with this difficulty, a network distillation operation that separates the low rank approximation and the weight quantization in the network training is introduced. The information from the initial LR-constrained NeRF (LR-NeRF) is distilled to a model of a much smaller dimension (DLR-NeRF) based on the TT decomposition of the LR-NeRF. An optimized global codebook is then learned to quantize all TT components, producing the final QDLR-NeRF. Experimental results show that this proposed method yields better compression efficiency compared to state-of-the-art methods and it also has the advantage of allowing the synthesis of any light field view with a high quality.



---

