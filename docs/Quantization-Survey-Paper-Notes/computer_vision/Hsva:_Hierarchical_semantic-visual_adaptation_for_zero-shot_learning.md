# Hsva: Hierarchical semantic-visual adaptation for zero-shot learning

## Summary

Summary: The paper proposes a hierarchical semantic-visual adaptation (HSV A) framework to mitigate the distribution disagreement issue between semantic and visual domains in zero-shot learning. The proposed framework adopts a two-step adaptation process, structure adaptation, and distribution adaptation, and uses supervised adversarial discrepancy (SAD) learning and Wasserstein distance to align semantic and visual domains. The proposed framework outperforms existing methods on conventional and generalized zero-shot learning tasks.


## Target Task

computer vision

## Content

<Abstract: >
Zero-shot learning (ZSL) is a technique to tackle the unseen class recognition problem by transferring semantic knowledge from seen classes to unseen ones. However, the existing common space learning methods in ZSL align semantic and visual domains by only mitigating distribution disagreement through one-step adaptation which is usually ineffective due to the heterogeneity of the feature representations in the two domains. To address this issue, the authors propose a hierarchical semantic-visual adaptation (HSV A) framework that aligns semantic and visual domains by adopting a two-step adaptation process, structure adaptation, and distribution adaptation. They use supervised adversarial discrepancy (SAD) learning to adversarially minimize the discrepancy between the predictions of two task-specific classifiers in the structure adaptation step. Finally, they minimize the Wasserstein distance between the latent multivariate Gaussian distributions to align visual and semantic distributions in the distribution adaptation step. The proposed framework achieves superior performance compared to existing methods on both conventional and generalized ZSL.



---

