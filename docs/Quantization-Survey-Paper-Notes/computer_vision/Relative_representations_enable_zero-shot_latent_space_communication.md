# Relative representations enable zero-shot latent space communication

## Summary

<Summary: >The authors propose the use of latent similarity between each sample and a fixed set of anchors as an alternative data representation. They demonstrate that it enforces the desired invariances without additional training, allowing for latent space communication and effective model stitching. They validate the capability of this approach on various datasets, modalities, tasks, and architectures.


## Target Task

computer vision

## Content

<Abstract: >Neural networks embed the geometric structure of a data manifold lying in a high-dimensional space into latent representations. Ideally, the distribution of the data points in the latent space should depend only on the task, the data, the loss, and other architecture-speciﬁc constraints. However, factors such as the random weights initialization, training hyperparameters, or other sources of randomness in the training phase may induce incoherent latent spaces that hinder any form of reuse. Nevertheless, we empirically observe that, under the same data and modeling choices, the angles between the encodings within distinct latent spaces do not change. In this work, we propose the latent similarity between each sample and a ﬁxed set of anchors as an alternative data representation, demonstrating that it can enforce the desired invariances without any additional training. We show how neural architectures can leverage these relative representations to guarantee, in practice, invariance to latent isometries and rescalings, effectively enabling latent space communication: from zero-shot model stitching to latent space comparison between diverse settings. We extensively validate the generalization capability of our approach on different datasets, spanning various modalities (images, text, graphs), tasks (e.g., classiﬁcation, reconstruction) and architectures (e.g., CNNs, GCNs, transformers).



---

