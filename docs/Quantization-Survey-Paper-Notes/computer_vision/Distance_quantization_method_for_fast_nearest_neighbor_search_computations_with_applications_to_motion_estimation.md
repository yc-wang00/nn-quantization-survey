# Distance quantization method for fast nearest neighbor search computations with applications to motion estimation

## Summary

Summary: This paper proposes an approach for reducing the complexity of finding the nearest neighbor of a query vector in a high-dimensional space. The approach involves applying non-uniform quantization within the metric computation process, which reduces the search metric computation resolution while preserving the minimum distance ranking. The proposed approach can significantly reduce the number and complexity of required arithmetic operations, does not increase complexity with the order of l p-norm, input bit size, or dimensionality, and has a small penalty in performance. The proposed approach is demonstrated through analytical and experimental studies using motion estimation and compensation for video coding as an example application.


## Target Task

computer vision

## Content

<Abstract:> The problem of finding the nearest neighbor of a query vector in a high dimensional space poses computational challenges due to the size of the database, dimensionality of the search space, and the metric complexity. While many existing algorithms reduce complexity by altering the dataset or computing the chosen distance metric to full precision, our proposed approach reduces complexity further by applying non-uniform quantization within the metric computation process. This reduces the search metric computation resolution while preserving the minimum distance ranking. Our approach can significantly reduce the number and complexity of required arithmetic operations, does not increase complexity with the order of l p-norm or input bit size, increases only slowly with dimensionality, and has a small penalty in performance if designed optimally. We present analytical and experimental studies of our proposed approach using motion estimation and compensation for video coding as an example application.



---

