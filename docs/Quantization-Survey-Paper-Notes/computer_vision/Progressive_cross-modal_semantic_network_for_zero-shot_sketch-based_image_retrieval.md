# Progressive cross-modal semantic network for zero-shot sketch-based image retrieval

## Summary

<Summary: >This paper proposes a novel progressive cross-modal semantic network for better zero-shot sketch-based image retrieval (ZS-SBIR) performance. The proposed method first explicitly aligns the sketch and image features to semantic features, then projects them to a common space for subsequent retrieval. The paper also employs cross-reconstruction loss to encourage aligned features to capture complete knowledge about the two modalities and multi-modal Euclidean loss that guarantees similarity between the retrieval features from a sketch-image pair. The proposed approach outperforms state-of-the-art competitors by more than 3% on the Sketchy dataset and about 6% on the TU-Berlin dataset in terms of retrieval accuracy.


## Target Task

computer vision

## Content

<Abstract: >Zero-shot sketch-based image retrieval (ZS-SBIR) is a specific cross-modal retrieval task that involves searching natural images through the use of free-hand sketches under the zero-shot scenario. Most previous methods project the sketch and image features into a low-dimensional common space for efficient retrieval and alignment to their semantic features (e.g., category-level word vectors) in order to transfer knowledge from seen to unseen classes. However, the lack of explicit alignment leads to unsatisfactory zero-shot retrieval performance. To address this issue, we propose a novel progressive cross-modal semantic network that first explicitly aligns the sketch and image features to semantic features, then projects the aligned features to a common space for subsequent retrieval. We further employ cross-reconstruction loss to encourage the aligned features to capture complete knowledge about the two modalities, along with multi-modal Euclidean loss that guarantees similarity between the retrieval features from a sketch-image pair. Our proposed approach outperforms state-of-the-art competitors to a remarkable extent by more than 3% on the Sketchy dataset and about 6% on the TU-Berlin dataset in terms of retrieval accuracy.



---

