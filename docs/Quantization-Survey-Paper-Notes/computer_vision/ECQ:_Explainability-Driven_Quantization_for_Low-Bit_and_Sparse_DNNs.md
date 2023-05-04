# ECQ: Explainability-Driven Quantization for Low-Bit and Sparse DNNs

## Summary

<Summary: >The paper proposes ECQx, a novel quantization method that uses Explainable AI (XAI) and information theory to generate ultra low-precision and sparse neural networks while maintaining or improving model performance. It assigns weight values based on weight relevances obtained from Layer-wise Relevance Propagation (LRP) and the information content of the clusters (entropy optimization) rather than just their distances to the quantization clusters. The method allows for highly compressible file sizes and is evaluated on different models and datasets.


## Target Task

computer vision

## Content

<Abstract: >The paper presents a novel quantization paradigm for DNNs called ECQx, which leverages concepts of Explainable AI (XAI) and information theory to generate ultra low-precision (2-5 bit) and sparse neural networks while maintaining or improving model performance. The method assigns weight values based on weight relevances obtained from Layer-wise Relevance Propagation (LRP) and the information content of the clusters (entropy optimization) rather than just their distances to the quantization clusters. The paper claims that the rendered networks are highly compressible in terms of file size, up to 103 compared to the full-precision unquantized DNN model. The approach was evaluated on different types of models and datasets and compared with previous work.



---

