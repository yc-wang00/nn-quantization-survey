# Vqvc+: One-shot voice conversion by vector quantization and u-net architecture

## Summary

Summary: The paper proposes a Voice Conversion (VC) method called VQVC+ which combines a Vector Quantization (VQ) based method with a U-Net architecture to address the issue of imperfect disentanglement of speaker and content in input speech during VC. The VQ serves as an information bottleneck to prevent overfitting, leading to excellent results in terms of audio naturalness and speaker similarity as compared to existing methods such as AutoVC and Chou.


## Target Task

speech recognition

## Content

<Abstract:>
Voice Conversion (VC) is a challenging task that transforms the voice of the source speaker while retaining the linguistic information. The disentangling of the speaker and content in input speech is carried out by vector quantization (VQ), adversarial training, or instance normalization (IN). However, the output speech quality is negatively affected due to imperfect disentanglement. To address this issue, the VQ-based method is combined with a U-Net architecture entitled VQVC+ in the proposed method. The VQ-based method serves as a strong information bottleneck that prevents overfitting. The proposed method shows excellent performance in both audio naturalness and speaker similarity over AutoVC and Chou by subjective evaluations.



---

