# TransZero++: Cross Attribute-Guided Transformer for Zero-Shot Learning

## Summary

Summary: The paper proposes a cross attribute-guided Transformer network named TransZero++ for accurate attribute localization in zero-shot learning tasks. The model uses feature-level and prediction-level losses to teach two attribute-guided transformers to learn visual embeddings and semantic knowledge representations collaboratively. These embeddings are fused with class semantic vectors for desirable visual-semantic interaction and ZSL classification.


## Target Task

computer vision

## Content

Abstract: —Zero-shot learning (ZSL) tackles the novel class recognition problem by transferring semantic knowledge from seen classes to unseen ones. Semantic knowledge is typically represented by attribute descriptions shared between different classes, which act as strong priors for localizing object attributes that represent discriminative region features, enabling significant and sufficient visual-semantic interaction for advancing ZSL. In this paper, we propose a cross attribute-guided Transformer network, termed TransZero++, to refine visual features and learn accurate attribute localization for key semantic knowledge representations in ZSL. By further introducing feature-level and prediction-level semantical collaborative losses, the two attribute-guided transformers teach each other to learn semantic-augmented visual embeddings for key semantic knowledge representations via semantical collaborative learning. Finally, the semantic-augmented visual embeddings learned by AVT and VAT are fused to conduct desirable visual-semantic interaction cooperated with class semantic vectors for ZSL classification.



---

