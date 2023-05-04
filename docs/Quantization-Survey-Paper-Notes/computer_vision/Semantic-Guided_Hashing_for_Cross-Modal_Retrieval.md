# Semantic-Guided Hashing for Cross-Modal Retrieval

## Summary

<Summary: >The paper proposes a two-step supervised cross-modal hashing approach named Semantic-Guided Hashing (SeGH) which addresses the problem of neglecting valuable semantic correlation among different classes in most existing supervised cross-modal hashing approaches. It takes the encoder-decoder paradigm based on label semantics obtained by the word vector of class names to learn the discriminative projection from original feature space to common semantic space in Step 1, and in Step 2, semantic representations of different modalities in the common space are projected into a Hamming space while preserving the intra-modality and inter-modality similarity. Results from experiments on two datasets show its superiority for cross-modal retrieval and effectiveness for zero-shot cross-modal retrieval against several state-of-the-art baselines.


## Target Task

computer vision

## Content

<Abstract: >In the Big Data era, cross-modal retrieval is a significant issue for retrieving heterogeneous or multimodal data. Cross-modal hashing has received considerable attention for effectively solving this issue by encoding high-dimensional data into compact binary codes. However, most existing supervised cross-modal hashing approaches only consider capturing the semantic information from original features to latent common semantic space, resulting in neglect of valuable semantic correlation among different classes. To address this problem, we propose a novel two-step supervised cross-modal hashing approach, termed Semantic-Guided Hashing (SeGH), which takes the encoder-decoder paradigm based on label semantics obtained by the word vector of class names to learn the discriminative projection from original feature space to common semantic space. In Step 2, semantic representations of different modalities in the common space are projected into a Hamming space while preserving the intra-modality and inter-modality similarity. The proposed SeGH has been compared against several state-of-the-art baselines on two datasets, and it showcases its superiority for cross-modal retrieval, as well as the effectiveness for zero-shot cross-modal retrieval with extensive experiments.



---

