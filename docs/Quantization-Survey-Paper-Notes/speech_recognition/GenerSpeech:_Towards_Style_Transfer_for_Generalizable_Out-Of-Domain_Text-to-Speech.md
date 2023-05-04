# GenerSpeech: Towards Style Transfer for Generalizable Out-Of-Domain Text-to-Speech

## Summary

<Summary: >The paper proposes GenerSpeech, a text-to-speech model for zero-shot style transfer of out-of-domain custom voices. It decomposes speech variations into style-agnostic and style-specific parts using a multi-level style adaptor and generalizable content adaptor with Mix-Style Layer Normalization. Evaluation shows that GenerSpeech outperforms state-of-the-art models in terms of audio quality and style similarity, and performs robustly in the few-shot data setting.


## Target Task

speech recognition

## Content

<Abstract: >Style transfer for out-of-domain (OOD) speech synthesis aims to generate speech samples with unseen style derived from an acoustic reference, while facing the following challenges: 1) The highly dynamic style features in expressive voice are difficult to model and transfer; and 2) the TTS models should be robust enough to handle diverse OOD conditions that differ from the source data. This paper proposes GenerSpeech, a text-to-speech model towards high-fidelity zero-shot style transfer of OOD custom voice. GenerSpeech decomposes the speech variation into the style-agnostic and style-specific parts by introducing two components: 1) a multi-level style adaptor to efficiently model a large range of style conditions, including global speaker and emotion characteristics, and the local (utterance, phoneme, and word-level) fine-grained prosodic representations; and 2) a generalizable content adaptor with Mix-Style Layer Normalization to eliminate style information in the linguistic content representation and thus improve model generalization. Our evaluations on zero-shot style transfer demonstrate that GenerSpeech surpasses the state-of-the-art models in terms of audio quality and style similarity. The extension studies to adaptive style transfer further show that GenerSpeech performs robustly in the few-shot data setting.



---

