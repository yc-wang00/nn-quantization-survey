# Adaptive Binary Quantization for Fast Nearest Neighbor Search.

## Summary

<Summary: >The paper proposes an adaptive binary quantization approach to generate discriminative binary codes using prototype-based hashing method. The approach learns a hash function that generates small unique binary codes for prototypes, addressing the problem of insufficient coding. Through alternating optimization, the method adapts to different prototype and binary code set sizes and can be generalized to the product space for long hash codes. Experiments on large-scale datasets show significant improvement relative to existing hashing methods.


## Target Task

computer vision

## Content

<Abstract: >Hashing has been proved an attractive technique for fast nearest neighbor search over big data. Compared to the projection based hashing methods, prototype based ones own stronger capability of generating discriminative binary codes for the data with complex inherent structure. However, our observation indicates that they still suffer from the insufficient coding that usually utilizes the complete binary codes in a hypercube. To address this problem, we propose an adaptive binary quantization method that learns a discriminative hash function with prototypes correspondingly associated with small unique binary codes. Our alternating optimization adaptively discovers the prototype set and the code set of a varying size in an efficient way, which together robustly approximate the data relations. Our method can be naturally generalized to the product space for long hash codes. We believe that our idea serves as a very helpful insight to hashing research. The extensive experiments on four large-scale (up to 80 million) datasets demonstrate that our method significantly outperforms state-of-the-art hashing methods, with up to 58.84% performance gains relatively.



---

