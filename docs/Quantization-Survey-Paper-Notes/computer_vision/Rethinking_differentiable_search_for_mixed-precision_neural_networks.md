# Rethinking differentiable search for mixed-precision neural networks

## Summary

<Summary: > The paper proposes a new approach for searching the optimal mixed-precision network search (MPS) problem, which is used to tune the bit-width to individual filter requirements. The proposed Efficient differentiable MIxed-Precision network Search (EdMIPS) method is effective in finding the optimal bit allocation for multiple popular deep neural networks, and can search a large model, e.g. Inception-V3, directly on ImageNet without proxy task in a reasonable amount of time. The learned mixed-precision networks outperform their uniform counterparts by accounting for different sensitivities of different filters.


## Target Task

computer vision

## Content

<Abstract: >Low-precision networks, with weights and activations quantized to low bit-width, are widely used to accelerate inference on edge devices. However, current solutions are uniform, using identical bit-width for all filters. This fails to account for the different sensitivities of different filters and is suboptimal. Mixed-precision networks address this problem, by tuning the bit-width to individual filter requirements. In this work, the problem of optimal mixed-precision network search (MPS) is considered. To circumvent its difficulties of discrete search space and combinatorial optimization, a new differentiable search architecture is proposed, with several novel contributions to advance the efficiency by leveraging the unique properties of the MPS problem. The resulting Efficient differentiable MIxed-Precision network Search (EdMIPS) method is effective at finding the optimal bit allocation for multiple popular networks, and can search a large model, e.g. Inception-V3, directly on ImageNet without proxy task in a reasonable amount of time. The learned mixed-precision networks significantly outperform their uniform counterparts.



---

