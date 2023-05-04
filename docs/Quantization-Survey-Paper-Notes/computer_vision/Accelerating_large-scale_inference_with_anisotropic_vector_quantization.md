# Accelerating large-scale inference with anisotropic vector quantization

## Summary

<Summary: >The paper proposes a new family of score-aware quantization loss functions that aim to minimize the quantization error for database points with higher inner products by penalizing the parallel component of a datapoint's residual relative to its orthogonal component. The researchers demonstrate that this approach leads to significant performance gains over traditional quantization methods in maximum inner product search tasks.


## Target Task

computer vision

## Content

<Abstract: >Quantization based techniques are currently used to scale maximum inner product search to massive databases. The objective of traditional quantization methods is to minimize the reconstruction error of database points. However, this is suboptimal for MIPS, as quantization error for database points with higher inner products is more important. In response, we propose a new family of score-aware quantization loss functions that can work under any weighting function of the inner product and regardless of whether the datapoints vary in norm. We demonstrate that these loss functions result in anisotropic weighting that more greatly penalizes the parallel component of a datapoint's residual relative to its orthogonal component. This leads to large MIPS performance gains over reconstruction loss.



---

