# Training robust zero-shot voice conversion models with self-supervised features

## Summary

Summary: The paper proposes an unsupervised zero-shot voice conversion model with a length resampling decoder that works with length-incompatible input and output features. It is trained on pairs of segments from the same utterance and adds a cycle-consistency loss following joint training with a speaker encoder and classification loss to improve audio quality. The proposed model shows significant performance improvement on VCTK and LibriTTS datasets.


## Target Task

speech recognition

## Content

<Abstract: >Unsupervised Zero-Shot Voice Conversion (VC) aims to modify the speaker characteristic of an utterance to match an unseen target speaker without relying on parallel training data. In this paper, we propose a VC model with a length resampling decoder that works with length-incompatible input and output features, allowing the self-supervised acoustic model and the vocoder to be trained on their task-optimal speech features. We also demonstrate that training on pairs of segments from the same utterance and adding a cycle-consistency loss can help to learn a lower variant speaker embedding, which leads to higher audio quality. Moreover, we show that training a speaker encoder jointly with a speaker classification loss produces utterances with better-transferred voice characteristics. We combine these training techniques and demonstrate performance improvement in terms of objective and subjective evaluation, on the VCTK dataset and the LibriTTS dataset.



---

