# Align and prompt: Video-and-language pre-training with entity prompts

## Summary

<Summary: >The paper proposes a new video-and-language pre-training framework called Align and Prompt (ALPRO) that aligns unimodal video-text features without explicit object detectors. This is achieved through a video-text contrastive (VTC) loss to align unimodal video-text features and a novel visually-grounded pre-training task that learns fine-grained alignment between visual region and text entity through an entity prompter module in a self-supervised way. The pre-trained model achieves state-of-the-art performance on both text-video retrieval and videoQA.


## Target Task

nlp

## Content

<Abstract: >Video-and-language pre-training has shown promising improvements on various downstream tasks. Most previous methods capture cross-modal interactions with a standard transformer-based multimodal encoder, not fully addressing the misalignment between unimodal video and text features. In this paper, we propose Align and Prompt: a new video-and-language pre-training framework (ALPRO), which operates on sparsely-sampled video frames and achieves more effective cross-modal alignment without explicit object detectors. First, we introduce a video-text contrastive (VTC) loss to align unimodal video-text features at the instance level, which eases the modeling of cross-modal interactions. Then, we propose a novel visually-grounded pre-training task, prompting entity modeling (PEM), which learns fine-grained alignment between visual region and text entity via an entity prompter module in a self-supervised way. Finally, we pretrain the video-and-language transformer models on large webly-source video-text pairs using the proposed VTC and PEM losses as well as two standard losses of masked language modeling (MLM) and video-text matching (VTM). The resulting pre-trained model achieves state-of-the-art performance on both text-video retrieval and videoQA, outperforming prior work by a substantial margin.



---

