# Optimizing jpeg quantization for classification networks

## Summary

Summary: The paper explores using customized Q-tables optimized for specific vision networks in JPEG compression for deep learning. A simple sorted random sampling method can exceed the performance of the standard JPEG Q-table, and hyper-parameter tuning techniques can improve the compression rate by 10% to 200% when accuracy is fixed or boost accuracy up to 2% at the same compression rate.


## Target Task

computer vision

## Content

<Abstract:>
Deep learning requires lossy image compression, specifically JPEG compression. The degree of quantization in JPEG is controlled by the Q-table, which determines the quality of the encoded image and compression ratio. In this work, we explore whether customized Q-tables optimized for specific vision networks can provide better quality-size trade-offs than those designed for human perception or minimal distortion. We reconstruct ImageNet test sets with higher resolution to test the effect of JPEG compression under novel Q-tables. We find that a simple sorted random sampling method can exceed the performance of the standard JPEG Q-table, and hyper-parameter tuning techniques can improve the compression rate by 10% to 200% when accuracy is fixed or boost accuracy up to 2% at the same compression rate.



---

