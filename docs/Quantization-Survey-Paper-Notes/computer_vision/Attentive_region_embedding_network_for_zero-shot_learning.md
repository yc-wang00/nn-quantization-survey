# Attentive region embedding network for zero-shot learning

## Summary

Summary: The paper proposes the attentive region embedding network (AREN) for zero-shot learning (ZSL) which utilizes local image regions (parts) to improve the semantic transfer between seen and unseen classes. AREN uses the attentive region embedding (ARE) and the attentive compressed second-order embedding (ACSE) streams to discover the semantic regions that have more discrimination power than attributes, and ACSE is incorporated to ensure stable semantic transfer. AREN sets a new benchmark for ZSL and achieves compelling results for generalized ZSL.


## Target Task

computer vision

## Content

<Abstract: >Zero-shot learning (ZSL) is a classification task that aims to recognize images from unseen categories by using only seen class images for training. Previous works on ZSL have mainly focused on global features or global regions to construct embeddings in the semantic space, but they do not explore the discrimination power of local image regions (parts), which can assist semantic transfer between seen and unseen classes. This paper proposes the attentive region embedding network (AREN) to discover semantic regions that correspond to semantic attributes and have stronger discrimination than attributes. AREN is end-to-end trainable and incorporates the attentive region embedding (ARE) stream and the attentive compressed second-order embedding (ACSE) stream. ARE discovers multiple part regions under the guidance of attention and compatibility loss, and an adaptive thresholding mechanism suppresses redundant attention regions. ACSE is also incorporated to guarantee more stable semantic transfer. AREN achieves state-of-the-art performance in evaluations on four benchmarks under ZSL setting and compelling results under generalized ZSL setting.



---

