# SpeechCLIP: Integrating Speech with Pre-Trained Vision and Language Model

## Summary

Summary: 
The paper proposes a framework called SpeechCLIP that connects speech and text through images to enhance speech models without transcriptions. The model aligns pre-trained HuBERT and CLIP models using paired images and spoken captions with minimal fine-tuning. The proposed model outperforms the prior state-of-the-art on image-speech retrieval and performs zero-shot speech-text retrieval without direct supervision from transcriptions. Visually grounded speech models (VGS) that utilize paired image-speech data to enhance speech processing are also discussed, and it is shown that VGS models trained with retrieval objectives can extract semantic and word-level information from speech.


## Target Task

speech recognition

## Content

<Abstract: >Data-driven speech processing models often require transcription data which is expensive to collect. In this paper, the authors propose SpeechCLIP, a framework that connects speech and text through images to enhance speech models without transcriptions. They align state-of-the-art pre-trained HuBERT and CLIP models using paired images and spoken captions with minimal fine-tuning. The proposed model outperforms prior state-of-the-art on image-speech retrieval and performs zero-shot speech-text retrieval without direct supervision from transcriptions. The model can extract semantically related keywords directly from speech. The authors also discuss the benefits of visually grounded speech models (VGS), which utilize paired image-speech data to enhance speech processing. They show that VGS models trained with retrieval objectives can extract semantic and word-level information from speech.



---

