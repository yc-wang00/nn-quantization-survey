# [PDF][PDF] Training deep learning recommendation model with quantized collective communications

## Summary

Summary: The paper discusses using integer quantization to reduce communication volume in synchronous training of DLRM. They explore quantizing alltoall and allreduce collectives and benchmark the accuracy loss with a representative DLRM model and Kaggle 7D dataset. Their results show that alltoall forward and backward passes, and dense allreduce can be quantized to 4 bits without accuracy loss compared to full-precision training.


## Target Task

computer vision

## Content

<Abstract:>
Deep Learning Recommendation Model (DLRM) captures our representative model architectures developed for click-through-rate (CTR) prediction based on high-dimensional sparse categorical data. Collective communications can account for a significant fraction of time in synchronous training of DLRM at scale. In this work, we explore using fine-grain integer quantization to reduce the communication volume of alltoall and allreduce collectives. We benchmark accuracy loss of quantized alltoall and allreduce with a representative DLRM model and Kaggle 7D dataset. We show that alltoall forward and backward passes, and dense allreduce can be quantized to 4 bits without accuracy loss compared to full-precision training.



---

