# Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers

## Summary

Summary: The paper proposes a language modeling approach for TTS using a neural codec language model called VALL-E. It involves training a model using discrete codes from a neural audio codec model and regarding TTS as a conditional language modeling task. During pre-training, the English speech database is scaled up to 60K hours. VALL-E can synthesize high-quality personalized speech with only a 3-second recording of an unseen speaker as an acoustic prompt. The experimental results show that VALL-E outperforms the state-of-the-art zero-shot TTS system in terms of speech naturalness and speaker similarity. Additionally, VALL-E preserves the speaker's emotion and acoustic environment of the acoustic prompt in synthesis.


## Target Task

speech recognition

## Content

<Abstract: >We introduce a language modeling approach for text to speech synthesis (TTS).
Speciﬁcally, we train a neural codec language model (called VALL-E ) using
discrete codes derived from an off-the-shelf neural audio codec model, and re-
gard TTS as a conditional language modeling task rather than continuous signal
regression as in previous work. During the pre-training stage, we scale up the TTS
training data to 60K hours of English speech which is hundreds of times larger than
existing systems. VALL-E emerges in-context learning capabilities and can be
used to synthesize high-quality personalized speech with only a 3-second enrolled
recording of an unseen speaker as an acoustic prompt. Experiment results show
that VALL-E signiﬁcantly outperforms the state-of-the-art zero-shot TTS system
in terms of speech naturalness and speaker similarity. In addition, we ﬁnd VALL-E
could preserve the speaker’s emotion and acoustic environment of the acoustic
prompt in synthesis. See https://aka.ms/valle for demos of our work.



---

