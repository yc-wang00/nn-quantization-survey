# Zero-shot long-form voice cloning with dynamic convolution attention

## Summary

<Summary: >This paper proposes an attention-based text-to-speech system that can reproduce a target voice from just a few seconds of reference speech and generalize to long utterances. It uses an energy-based attention mechanism for generalization and conditional pretraining on a large corpus of diverse data to achieve effective zero-shot speaker adaptation. The proposed model outperforms several implementations of voice cloning systems in terms of speech naturalness, speaker similarity, alignment consistency, and ability to synthesize long utterances.


## Target Task

speech recognition

## Content

<Abstract: >With recent advancements in voice cloning, the performance of speech synthesis for a target speaker has been rendered similar to the human level. However, autoregressive voice cloning systems still suffer from text alignment failures, resulting in an inability to synthesize long sentences. In this work, we propose a variant of attention-based text-to-speech system that can reproduce a target voice from a few seconds of reference speech and generalize to very long utterances as well. The proposed system is based on three independently trained components: a speaker encoder, synthesizer and universal vocoder. Generalization to long utterances is realized using an energy-based attention mechanism known as Dynamic Convolution Attention, in combination with a set of modifications proposed for the synthesizer based on Tacotron 2. Moreover, effective zero-shot speaker adaptation is achieved by conditioning both the synthesizer and vocoder on a speaker encoder that has been pretrained on a large corpus of diverse data. We compare several implementations of voice cloning systems in terms of speech naturalness, speaker similarity, alignment consistency and ability to synthesize long utterances, and conclude that the proposed model can produce intelligible synthetic speech for extremely long utterances, while preserving a high extent of naturalness and similarity for short texts.



---

