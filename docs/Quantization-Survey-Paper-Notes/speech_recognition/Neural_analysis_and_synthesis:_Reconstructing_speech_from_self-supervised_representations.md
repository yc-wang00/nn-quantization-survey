# Neural analysis and synthesis: Reconstructing speech from self-supervised representations

## Summary

<Summary: >The paper introduces a neural analysis and synthesis framework called NANSY that can manipulate voice, speed and pitch of speech signals with high reconstruction quality and controllability. Unlike previous works, this framework does not use any bottleneck structures for disentangling analysis features. It uses a novel training strategy based on information perturbation and features including wav2vec and newly proposed pitch feature called Yingram for self-supervised training. NANSY can also be extended to a multilingual setting. The framework performs well in several applications such as pitch shift, time-scale modification, and zero-shot voice conversion.


## Target Task

speech recognition

## Content

<Abstract: >We present a neural analysis and synthesis (NANSY) framework for manipulating voice, pitch and speed of any given speech signal. We address the poor reconstruction quality obtained from previous works that used information bottleneck to disentangle analysis features for controllable synthesis, by proposing a novel training strategy based on information perturbation. NANSY does not require any bottleneck structures and enjoys high reconstruction quality and controllability. The framework utilizes a new set of analysis features – wav2vec feature and newly proposed pitch feature, Yingram, which allows for fully self-supervised training. NANSY can be extended to a multilingual setting by training on a multilingual dataset. The experiments show that NANSY achieves significant improvement in performance in several applications such as zero-shot voice conversion, pitch shift, and time-scale modification.



---

