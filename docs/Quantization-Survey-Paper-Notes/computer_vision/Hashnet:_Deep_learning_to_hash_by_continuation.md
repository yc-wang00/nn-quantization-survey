# Hashnet: Deep learning to hash by continuation

## Summary

Summary: The paper presents HashNet, a novel deep architecture for deep learning to hash that learns exactly binary hash codes from imbalanced similarity data. It uses a continuation method with convergence guarantees to address the ill-posed gradient difficulty in optimization with sign activations. HashNet can generate exactly binary hash codes and outperforms existing deep learning to hash methods on standard benchmarks.


## Target Task

computer vision

## Content

<Abstract:>
Learning to hash has been widely applied to approxi-
mate nearest neighbor search for large-scale multimedia re-
trieval, due to its computation efﬁciency and retrieval qual-
ity. Deep learning to hash, which improves retrieval quality
by end-to-end representation learning and hash encoding,
has received increasing attention recently. Subject to the ill-
posed gradient difﬁculty in the optimization with sign acti-
vations, existing deep learning to hash methods need to ﬁrst
learn continuous representations and then generate binary
hash codes in a separated binarization step, which suffer
from substantial loss of retrieval quality. This work presents
HashNet, a novel deep architecture for deep learning to
hash by continuation method with convergence guarantees,
which learns exactly binary hash codes from imbalanced
similarity data. Comprehensive empirical evidence shows that
HashNet can generate exactly binary hash codes and yield state-
of-the-art multimedia retrieval performance on standard benchmarks.



---

