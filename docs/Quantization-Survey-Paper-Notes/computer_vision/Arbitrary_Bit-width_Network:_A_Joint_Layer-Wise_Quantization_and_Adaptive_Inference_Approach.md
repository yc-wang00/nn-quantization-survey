# Arbitrary Bit-width Network: A Joint Layer-Wise Quantization and Adaptive Inference Approach

## Summary

<Summary: >The paper proposes the Arbitrary Bit-width Network (ABN) which suggests using varying quantization schemes for different data samples, which may vary in recognition difficulty. This approach achieves data-dependent dynamic inference at the layer level. ABN utilizes a Markov Decision Process (MDP) to help determine the runtime bit-width for each layer based on well-trained super-network. The proposed technique resulted in 1.1% top1 accuracy improvement while saving 36.2% BitOps on ImageNet classification.


## Target Task

computer vision

## Content

<Abstract: >Conventional model quantization methods use a fixed quantization scheme to different data samples, which ignores the inherent “recognition difficulty” differences between various samples. We propose to feed different data samples with varying quantization schemes to achieve a data-dependent dynamic inference, at a fine-grained layer level. To solve this problem, we present the Arbitrary Bit-width Network (ABN), where the bit-widths of a single deep network can change at runtime for different data samples, with a layer-wise granularity. Based on the well-trained super-network, each layer’s runtime bit-width selection decision is modeled as a Markov Decision Process (MDP) and solved by an adaptive inference strategy accordingly. On ImageNet classification, we achieve 1.1% top1 accuracy improvement while saving 36.2% BitOps.



---

