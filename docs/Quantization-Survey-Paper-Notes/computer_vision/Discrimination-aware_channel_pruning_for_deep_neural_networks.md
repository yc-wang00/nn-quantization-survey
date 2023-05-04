# Discrimination-aware channel pruning for deep neural networks

## Summary

<Summary: >The paper introduces a new approach for deep model compression called discrimination-aware channel pruning (DCP). This approach uses discrimination-aware losses to increase the discriminative power of intermediate layers and select the most discriminative channels for each layer. A greedy algorithm is proposed for channel selection and parameter optimization. Experiments show that DCP is effective, achieving a pruned ResNet-50 with a 0.39% improvement in top-1 accuracy on ILSVRC-12 with a 30% reduction of channels.


## Target Task

computer vision

## Content

<Abstract: >Channel pruning is an effective approach for deep model compression, but existing methods have limitations such as computational expense and ignoring the discriminative power of channels. In this paper, we propose discrimination-aware channel pruning (DCP) which introduces discrimination-aware losses into the network to increase the discriminative power of intermediate layers and select the most discriminative channels for each layer by considering the additional loss and reconstruction error. A greedy algorithm is proposed for channel selection and parameter optimization. Experiments demonstrate the effectiveness of DCP, with a pruned ResNet-50 achieving a 0.39% improvement in top-1 accuracy on ILSVRC-12 with a 30% reduction of channels.



---

