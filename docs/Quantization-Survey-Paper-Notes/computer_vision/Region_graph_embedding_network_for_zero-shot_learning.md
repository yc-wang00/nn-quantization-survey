# Region graph embedding network for zero-shot learning

## Summary

Summary: This paper proposes a region-based relation reasoning method called Region Graph Embedding Network (RGEN) for Zero-Shot Learning. The proposed method incorporates region-based relation reasoning in ZSL by representing the local image regions as a graph, on which the parts relation reasoning is performed with graph convolutions. The proposed method is validated through experiments conducted on four datasets under both ZSL and generalized ZSL settings.


## Target Task

computer vision

## Content

<Abstract: >Most of the existing Zero-Shot Learning (ZSL) approaches learn direct embeddings from global features or image parts (regions) to the semantic space, which, however, fail to capture the appearance relationships between different local regions within a single image. In this paper, to model the relations among local image regions, we incorporate the region-based relation reasoning into ZSL. Our method, termed as Region Graph Embedding Network (RGEN), is trained end-to-end from raw image data. Specifically, RGEN consists of two branches: the Constrained Part Attention (CPA) branch and the Parts Relation Reasoning (PRR) branch. CPA branch is built upon attention and produces the image regions. To exploit the progressive interactions among these regions, we represent them as a region graph, on which the parts relation reasoning is performed with graph convolutions, thus leading to our PRR branch. To train our model, we introduce both a transfer loss and a balance loss to contrast class similarities and pursue the maximum response consistency among seen and unseen outputs, respectively. Extensive experiments on four datasets well validate the effectiveness of the proposed method under both ZSL and generalized ZSL settings.



---

