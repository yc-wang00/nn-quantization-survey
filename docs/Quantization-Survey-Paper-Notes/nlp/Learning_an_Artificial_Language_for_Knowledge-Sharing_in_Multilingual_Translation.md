# Learning an Artificial Language for Knowledge-Sharing in Multilingual Translation

## Summary

Summary: This paper proposes a method to discretize the encoder output latent space of multilingual models by assigning encoder states to entries in a codebook to improve the learning of a common representation, which increases robustness in unseen testing conditions. The approach is validated through large-scale experiments and is competitive with strong alternatives from literature in zero-shot conditions. Furthermore, the authors use the learned artificial language to analyze model behavior and find that using a similar bridge language increases knowledge-sharing among the remaining languages.


## Target Task

nlp

## Content

<Abstract: >The cornerstone of multilingual neural translation is shared representations across languages. Given the theoretically infinite representation power of neural networks, semantically identical sentences are likely represented differently. While representing sentences in the continuous latent space ensures expressiveness, it introduces the risk of capturing of irrelevant features which hinders the learning of a common representation. In this work, we discretize the encoder output latent space of multilingual models by assigning encoder states to entries in a codebook, which in effect represents source sentences in a new artificial language. This discretization process not only offers a new way to interpret the otherwise black-box model representations, but, more importantly, gives potential for increasing robustness in unseen testing conditions. We validate our approach on large-scale experiments with realistic data volumes and domains. When tested in zero-shot conditions, our approach is competitive with two strong alternatives from the literature. We also use the learned artificial language to analyze model behavior, and discover that using a similar bridge language increases knowledge-sharing among the remaining languages.



---

