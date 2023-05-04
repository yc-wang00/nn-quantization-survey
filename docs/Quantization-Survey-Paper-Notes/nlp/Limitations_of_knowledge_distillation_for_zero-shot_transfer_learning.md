# Limitations of knowledge distillation for zero-shot transfer learning

## Summary

Summary: This paper highlights the limitations of knowledge distillation for zero-shot transfer learning in multilingual pretrained transformer-based encoders such as mBERT, and evaluates the effectiveness of knowledge distillation during pretraining and fine-tuning stages. It indicates that distillation during pretraining is more effective than during fine-tuning for zero-shot transfer learning in multilingual settings. The paper also demonstrates that distillation during fine-tuning may harm zero-shot cross-lingual performance. The study concludes that distilling a larger model (BERT Large) yields the strongest distilled model that performs well both on the source language and the target languages in zero-shot settings.


## Target Task

nlp

## Content

<Abstract:> This paper discusses the limitations of knowledge distillation for zero-shot transfer learning in multilingual pretrained transformer-based encoders such as mBERT. The paper evaluates the effectiveness of knowledge distillation during pretraining and fine-tuning stages and shows that in multilingual settings, distillation during pretraining is more effective than distillation during fine-tuning for zero-shot transfer learning. The paper also demonstrates that in some cases, distillation during fine-tuning may harm zero-shot cross-lingual performance. Finally, the paper concludes that distilling a larger model (BERT Large) results in the strongest distilled model that performs best both on the source language as well as target languages in zero-shot settings.



---

