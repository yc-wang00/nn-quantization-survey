# Vector-quantized neural networks for acoustic unit discovery in the zerospeech 2020 challenge

## Summary

Summary: The paper proposes two neural models to discover acoustic units from unlabelled speech data. These models use vector quantization to map continuous features to a finite set of codes. The first model is a type of vector-quantized variational autoencoder(VQ-VAE) and the second model combines vector quantization with contrastive predictive coding (VQ-CPC). Both models outperformed all submissions to the 2019 and 2020 challenges for ABX phone discrimination tests with a relative improvement of more than 30%. VQ-CPC performs slightly better and is simpler and faster to train than VQ-VAE. The paper concludes that vector quantization is an effective bottleneck that forces the models to discard speaker information.


## Target Task

speech recognition

## Content

<Abstract: >In this paper, we explore vector quantization for acoustic unit discovery. Leveraging unlabelled data, we aim to learn discrete representations of speech that separate phonetic content from speaker-specific details. We propose two neural models to tackle this challenge – both use vector quantization to map continuous features to a finite set of codes. The first model is a type of vector-quantized variational autoencoder (VQ-VAE). The VQ-VAE encodes speech into a sequence of discrete units before reconstructing the audio waveform. Our second model combines vector quantization with contrastive predictive coding (VQ-CPC). The idea is to learn a representation of speech by predicting future acoustic units. We evaluate the models on English and Indonesian data for the ZeroSpeech 2020 challenge. In ABX phone discrimination tests, both models outperform all submissions to the 2019 and 2020 challenges, with a relative improvement of more than 30%. The models also perform competitively on a downstream voice conversion task. Of the two, VQ-CPC performs slightly better in general and is simpler and faster to train. Finally, probing experiments show that vector quantization is an effective bottleneck, forcing the models to discard speaker information.



---

