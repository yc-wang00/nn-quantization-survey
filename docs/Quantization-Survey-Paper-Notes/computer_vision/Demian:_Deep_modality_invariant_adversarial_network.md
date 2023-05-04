# Demian: Deep modality invariant adversarial network

## Summary

Summary: The paper proposes a method for obtaining common representations from different modalities, called modality-invariant representations, using a novel algorithm called Deep Modality Invariant Adversarial Network (DeMIAN). DeMIAN utilizes the idea of Domain Adaptation (DA) and achieved better classification accuracy than the state-of-the-art methods, particularly for benchmark datasets of zero-shot learning. The authors suggest that this method is more straightforward than addressing labeled multi-modal data.


## Target Task

computer vision

## Content

<Abstract: >
Obtaining common representations from different
modalities is important in that they are interchangeable
with each other in a classiﬁcation problem. For example,
we can train a classiﬁer on image features in the common
representationsandapplyittothetestingofthetextfeatu res
in the representations. Existing multi-modalrepresentat ion
learning methods mainly aim to extract rich information
from paired samples and train a classiﬁer by the cor-
responding labels; however, collecting paired samples
and their labels simultaneously involves high labor costs.
Addressing paired modal samples without their labels and
single modal data with their labels independently is much
easierthanaddressinglabeledmulti-modaldata. Toobtain
the common representations under such a situation, we
propose to make the distributions over different modalitie s
similar in the learned representations, namely modality-
invariantrepresentations. Inparticular,weproposeanov el
algorithm for modality-invariant representation learnin g,
named Deep Modality Invariant Adversarial Network
(DeMIAN), which utilizes the idea of Domain Adaptation
(DA).Usingthemodality-invariantrepresentationslearn ed
by DeMIAN, we achieved better classiﬁcation accuracy
than with the state-of-the-art methods, especially for som e
benchmarkdatasetsofzero-shotlearning.



---

