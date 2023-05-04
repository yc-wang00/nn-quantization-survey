# Span pointer networks for non-autoregressive task-oriented semantic parsing

## Summary

Summary: The paper proposes a non-autoregressive parser, called span pointer networks that can map utterances to semantic frames in three steps with less latency and memory usage compared to prior non-autoregressive parsers. The proposed parser achieves 87 EM on TOPv2 after evaluating on several task-oriented semantic parsing datasets.


## Target Task

nlp

## Content

<Abstract: >An effective recipe for building seq2seq, non-autoregressive, task-oriented parsers to map utterances to semantic frames proceeds in three steps: encoding an utterance x, predicting a frame’s length jyj, and decoding ajyj-sized frame with utterance and ontology tokens. We propose span pointer networks, non-autoregressive parsers which shift the decoding task from text generation to span prediction. We evaluate our approach on several task-oriented semantic parsing datasets, achieving 87 EM on TOPv2. We observe a 70% reduction in latency and 83% in memory at beam size 5 compared to prior non-autoregressive parsers.



---

