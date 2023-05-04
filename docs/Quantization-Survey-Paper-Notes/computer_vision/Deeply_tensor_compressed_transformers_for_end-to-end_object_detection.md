# Deeply tensor compressed transformers for end-to-end object detection

## Summary

Summary: This paper proposes a method for compressing DETR models used in object detection pipelines by using low-rank tensor decomposition. Through experiments on the COCO dataset, the authors demonstrate that their method can achieve more than 3x compression with minimal loss in accuracy.


## Target Task

computer vision

## Content

<Abstract: >
DEtection TRansformer (DETR) is a recently proposed method that streamlines the detection pipeline without complex anchor generation and post-processing procedures, making the detection pipeline more intuitive. However, the numerous redundant parameters in transformers make the DETR models computation and storage intensive, which hinders them from being deployed on resources-constrained devices. To obtain a compact end-to-end detection framework, a proposed deeply compressed transformer with low-rank tensor decomposition can achieve significant parameter and model size reduction while maintaining high detection performance. The proposed method is validated on the COCO dataset through extensive experiments. The experimental results show that 3.7× full model compression can be attained with 482× feed forward network (FFN) parameter reduction and only 0.6 points accuracy drop.



---

