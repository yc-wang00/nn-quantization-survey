# Data efficient language-supervised zero-shot recognition with optimal transport distillation

## Summary

<Summary:>
The paper proposes a method called OTTER that uses online entropic optimal transport to find soft image-text match as labels for contrastive learning, achieving strong zero-shot recognition performance compared to InfoNCE loss, label smoothing and knowledge distillation on Google Open Images and multi-labeled ImageNet. Source code for OTTER is available on Github.


## Target Task

computer vision

## Content

<Abstract:>
We propose OTTER (Optimal Transport Distillation for Efficient Zero-Shot Recognition), which uses online entropic optimal transport to find a soft image-text match as labels for contrastive learning. Based on pretrained image and text encoders, models trained with OTTER achieve strong performance with only 3M image text pairs. Compared with InfoNCE loss, label smoothing, and knowledge distillation, OTTER consistently outperforms these baselines in zero-shot evaluation on Google Open Images (19,958 classes) and multi-labeled ImageNet 10K (10032 classes) from Tencent ML-Images. Our source code is open sourced at https://github.com/facebookresearch/OTTER.



---

