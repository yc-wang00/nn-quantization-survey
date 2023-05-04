# Eva: Exploring the limits of masked visual representation learning at scale

## Summary

Summary: The paper introduces EVA, a ViT-based model pre-trained to reconstruct masked out image-text aligned vision features to scale up to one billion parameters. It is capable of achieving state-of-the-art performance on various vision-related downstream tasks without extensive supervised training. The authors also demonstrate that changes in scaling EVA can result in qualitative changes in transfer learning performance. The paper includes the release of the code and its billion-scale models.


## Target Task

computer vision

## Content

<Abstract:>
We launch EVA, a vanilla ViT-based model that explores the limits of visual representation by using only publicly accessible data. EVA is pre-trained to reconstruct the masked out image-text aligned vision features, conditioned on visible image patches. Via this pretext task, we can efficiently scale up EVA to one billion parameters and set new records on a broad range of representative vision downstream tasks such as image recognition, video action recognition, object detection, instance segmentation, and semantic segmentation, without heavy supervised training. EVA can also serve as a vision-centric, multi-modal pivot to connect images and text. We observe quantitative changes in scaling EVA result in qualitative changes in transfer learning performance that are not present in other models. To facilitate future research, we release all the code and billion-scale models.



---

