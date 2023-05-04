# Streaming end-to-end speech recognition for mobile devices

## Summary

<Summary: >The paper presents a novel approach for end-to-end speech recognition using a recurrent neural network transducer with layer normalization, large batch size, word-piece targets, time reduction and quantization. Synthetic data is used to train the model with better accuracy, while shallow fusion is used for bias towards user-specific context. The proposed approach outperforms the conventional CTC-based model in terms of latency and accuracy in voice search and dictation.


## Target Task

speech recognition

## Content

<Abstract: >End-to-end models are promising for on-device speech recognition, but require streaming decoding, robustness to diverse use cases, and user-specific context in addition to high accuracy. We present a recurrent neural network transducer-based end-to-end speech recognizer with layer normalization, large batch size, word-piece targets, time reduction and quantization. Shallow fusion is also used for bias towards user-specific context. Training the model on synthetic data generated using a text-to-speech system addresses the model's inability to accurately model numeric sequences. Results show that our proposed approach outperforms a conventional CTC-based model in terms of latency and accuracy in several evaluation categories, including voice search and dictation.



---

