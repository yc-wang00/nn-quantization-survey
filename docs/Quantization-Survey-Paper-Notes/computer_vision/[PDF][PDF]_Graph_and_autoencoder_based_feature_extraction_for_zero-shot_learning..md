# [PDF][PDF] Graph and autoencoder based feature extraction for zero-shot learning.

## Summary

<Summary: > The paper proposes a framework called Graph and Autoencoder Based Feature Extraction (GAFE) to improve Zero-shot learning (ZSL) imaging recognition of novel categories without training data. GAFE preserves the sub-manifold of samples in the embedding space and ensures that the mapping can precisely reconstruct the original visual feature. GAFE combines encoder and decoder parts, constructs a graph to preserve the local intrinsic structure of the data, and imposes an L21 norm sparsity constraint on the mapping to identify relevant features to the target domain, and achieves better results in five attribute datasets.


## Target Task

computer vision

## Content

<Abstract: >Zero-shot learning (ZSL) refers to models built to recognize novel visual categories that have no associated labelled training samples. Existing approaches, however, fail to preserve the sub-manifold of samples in the embedding space and do not investigate whether the mapping can precisely reconstruct the original visual feature. In this paper, the authors propose a Graph and Autoencoder Based Feature Extraction (GAFE) framework to address these issues. GAFE seeks a low-rank mapping to preserve the sub-manifold of samples by taking the encoder-decoder paradigm. The encoder part learns a mapping from the visual feature to the semantic space, while the decoder part reconstructs the original features with the learned mapping. Moreover, GAFE constructs a graph to guarantee the learned mapping can preserve the local intrinsic structure of the data, and an L21 norm sparsity constraint is imposed on the mapping to identify features relevant to the target domain. The effectiveness of the proposed model is demonstrated through extensive experiments on ﬁve attribute datasets.



---

