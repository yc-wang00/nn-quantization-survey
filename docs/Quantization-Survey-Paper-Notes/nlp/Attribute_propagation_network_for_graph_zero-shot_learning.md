# Attribute propagation network for graph zero-shot learning

## Summary

Summary: The paper proposes an attribute propagation network (APNet) to improve zero-shot learning (ZSL) by refining the semantic attributes of each class based on its neighbors and related classes on a graph of classes. The APNet is composed of a graph propagation model and a parameterized nearest neighbor (NN) classifier. The paper introduces a meta-learning strategy to train the propagation mechanism and the similarity metric for the NN classifier on multiple sub-graphs. The APNet achieves compelling performance or new state-of-the-art results in experiments with two ZSL settings and five benchmark datasets.


## Target Task

nlp

## Content

<Abstract:>
The paper proposes an attribute propagation network (APNet) to optimize the attribute space for zero-shot learning (ZSL) by training a propagation mechanism to refine the semantic attributes of each class based on its neighbors and related classes on a graph of classes. The propagated attributes can produce classifiers for zero-shot classes with significantly improved performance in different ZSL settings. The APNet is composed of a graph propagation model generating attribute vectors for each class and a parameterized nearest neighbor (NN) classifier categorizing an image to the class with the nearest attribute vector to the image’s embedding. The paper also introduces a meta-learning strategy to train the propagation mechanism and the similarity metric for the NN classifier on multiple sub-graphs, each associated with a classification task over a subset of training classes. The APNet achieves compelling performance or new state-of-the-art results in experiments with two zero-shot learning settings and five benchmark datasets.



---

