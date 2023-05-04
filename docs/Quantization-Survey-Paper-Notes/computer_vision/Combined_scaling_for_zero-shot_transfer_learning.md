# Combined scaling for zero-shot transfer learning

## Summary

Summary: The paper introduces BASIC, a combined scaling method for contrastive learning that achieves a top-1 accuracy of 85.7% on the ImageNet ILSVRC-2012 validation set without learning from any labeled ImageNet data. BASIC surpasses previously published similar models, CLIP and ALIGN, by 9.3%. The authors scale up the contrastive learning framework by increasing data size, model size, and batch size, and propose methods such as gradient checkpointing and model parallelism to overcome memory limitations. They also show that larger contrastive batch sizes lead to smaller generalization gaps for image-text models.


## Target Task

computer vision

## Content

<Abstract: >
We present BASIC, a combined scaling method that achieves 85.7% top-1 accuracy on ImageNet ILSVRC-2012 validation set without learning from any labeled ImageNet example. BASIC surpasses best-published similar models - CLIP and ALIGN by 9.3%. Our BASIC model also shows significant improvements in robustness benchmarks like ImageNet-{A,R,V2,Sketch} and ObjectNet. To achieve these results, we scale up the contrastive learning framework of CLIP and ALIGN in three dimensions: data size, model size, and batch size. We encountered two main challenges, the limited memory of accelerators, such as GPUs and TPUs, and the effect of a large contrastive batch size on such contrastive-trained image-text models is not well-understood. To overcome these challenges, we propose two simple methods which make use of gradient checkpointing and model parallelism, and a theoretical framework that shows larger contrastive batch sizes lead to smaller generalization gaps for image-text models.



---

