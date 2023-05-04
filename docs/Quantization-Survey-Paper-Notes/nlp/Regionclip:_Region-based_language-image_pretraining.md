# Regionclip: Region-based language-image pretraining

## Summary

<Summary: >The paper discusses the limitations of contrastive language-image pretraining (CLIP) on fine-grained object detection due to domain shift, and proposes a solution called RegionCLIP which extends CLIP to learn region-level visual representations, enabling proper alignment between image regions and textual concepts.


## Target Task

nlp

## Content

<Abstract: >Contrastive language-image pretraining (CLIP) using
image-text pairs has achieved impressive results on image
classification in both zero-shot and transfer learning set-
tings. However, we show that directly applying such mod-
els to recognize image regions for object detection leads to
unsatisfactory performance due to a major domain shift:
CLIP was trained to match an image as a whole to a text de-
scription, without capturing the fine-grained alignment be-
tween image regions and text spans. To mitigate this issue,
we propose a new method called RegionCLIP that signifi-
cantly extends CLIP to learn region-level visual representa-
tions, thus enabling fine-grained alignment between image
regions and textual concepts.



---

