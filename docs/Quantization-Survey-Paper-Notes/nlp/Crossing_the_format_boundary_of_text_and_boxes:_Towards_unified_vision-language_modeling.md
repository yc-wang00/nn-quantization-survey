# Crossing the format boundary of text and boxes: Towards unified vision-language modeling

## Summary

<Summary:> The paper proposes a UniTAB model that unifies text and box outputs for grounded vision-language modeling. The model generates a text and aligns predicted words with object regions using a shared token sequence, introducing a special "<obj>" token to indicate word-box alignments naturally. UniTAB provides a more comprehensive and interpretable image description, outperforming state-of-the-art models in grounded captioning evaluations. In general VL tasks, UniTAB achieves better or comparable performance than task-specific models.


## Target Task

nlp

## Content

<Abstract:> We propose UniTAB that Unifies Text And Box outputs for grounded vision-language (VL) modeling. Grounded VL tasks such as grounded captioning require the model to generate a text description and align predicted words with object regions. To achieve this, models must generate desired text and box outputs together, and meanwhile indicate the alignments between words and boxes. UniTAB represents both text and box outputs with a shared token sequence, and introduces a special <obj> token to naturally indicate word-box alignments in the sequence. UniTAB thus could provide a more comprehensive and interpretable image description, by freely grounding generated words to object regions. On grounded captioning, UniTAB presents a simpler solution with a single output head, and significantly outperforms state of the art in both grounding and captioning evaluations. On general VL tasks that have different desired output formats ( i.e., text, box, or their combination), UniTAB with a single network achieves better or comparable performance than task-specific state of the art.



---

