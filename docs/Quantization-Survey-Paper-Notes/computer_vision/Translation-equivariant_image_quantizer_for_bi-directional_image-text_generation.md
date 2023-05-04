# Translation-equivariant image quantizer for bi-directional image-text generation

## Summary

<Summary: >This paper proposes a solution to achieve translation-equivariant image quantization through enforcing orthogonality among codebook embeddings. Three proof-of-concept experiments were conducted to analyze sample efficiency and effectiveness of the solution, which showed that translation-equivariant image quantization improves both sample efficiency and accuracy over VQGAN. The paper also discusses limitations of representing images with quantized indices in downstream tasks and demonstrates that current image quantization methods fail to satisfy translation equivariance due to aliasing caused by downsampling operations.


## Target Task

computer vision

## Content

<Abstract: > This paper presents a study on image quantization and explores the issue of translation equivariance. The authors propose a solution to achieve translation-equivariant image quantization by enforcing orthogonality among the codebook embeddings. The paper presents three proof-of-concept experiments to analyze sample efficiency and test the proposed solution's effectiveness. The experiments show that translation-equivariant image quantization improves not only sample efficiency but also accuracy over VQGAN. The paper discusses the two-stage approach of image quantization and downstream tasks, and how the idea of representing images with quantized indices has limitations due to broken translation equivariance in the quantized space. The paper demonstrates that current image quantization methods fail to satisfy translation equivariance due to aliasing caused by downsampling operations.



---

