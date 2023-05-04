# Improving the Cross-Lingual Generalisation in Visual Question Answering

## Summary

<Summary: >The paper proposes three strategies to improve cross-lingual transfer of multilingual vision-language pretrained models in a zero-shot cross-lingual VQA task, including introducing a linguistic prior objective, learning a task-specific subnetwork, and augmenting training examples using synthetic code-mixing. These strategies are shown to be effective in improving performance and outperform existing methods with sparse models on 7 typologically diverse languages.


## Target Task

nlp

## Content

<Abstract: >In this research paper, the authors address the low performance of multilingual vision-language pretrained models on cross-lingual visual question answering (VQA) tasks. They explore the poor performance of such models on a zero-shot cross-lingual VQA task, where the models are fine-tuned on English visual-question data and evaluated on 7 typologically diverse languages. They propose three strategies to improve cross-lingual transfer: (1) introducing a linguistic prior objective to augment the cross-entropy loss, (2) learning a task-specific subnetwork to improve cross-lingual generalisation, and (3) augmenting training examples using synthetic code-mixing to promote alignment of embeddings between source and target languages. Their experiments on xGQA demonstrate the effectiveness of the proposed fine-tuning strategy for 7 languages, outperforming existing transfer methods with sparse models.



---

