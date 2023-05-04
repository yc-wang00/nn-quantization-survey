# Visually-augmented language modeling

## Summary

Summary: The paper proposes a pre-training framework called VALM, which utilizes visually-augmented text tokens for language modeling by retrieving relevant images. This approach enables multimodal grounded language modeling by attending to both text and visual knowledge in images. The proposed VALM outperforms strong language-only and vision-language baselines on various visual knowledge-intensive commonsense reasoning tasks, demonstrating substantial gains in reasoning object commonsense including color, size, and shape.


## Target Task

nlp

## Content

<Abstract: >Human language is grounded on multimodal knowledge including visual knowledge like colors, sizes, and shapes. However, current large-scale pre-trained language models rely on text-only self-supervised training with massive text data, which precludes them from utilizing relevant visual information when necessary. To address this, we propose a novel pre-training framework, named VALM, to visually-augment text tokens with retrieved relevant images for Language Modeling. Specifically, VALM builds on a novel latent text-image alignment method via an image retrieval module to fetch corresponding images given a textual context. With the visually-augmented context, VALM uses a visual knowledge fusion layer to enable multimodal grounded language modeling by attending to both text context and visual knowledge in images. We evaluate VALM on various visual knowledge-intensive commonsense reasoning tasks, which require visual information to excel. The experimental results illustrate that VALM outperforms all strong language-only and vision-language baselines with substantial gains in reasoning object commonsense including color, size, and shape.



---

