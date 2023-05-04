# Quantization guided jpeg artifact correction

## Summary

<Summary: > The paper discusses the limitations of the JPEG image compression algorithm due to information loss resulting in reduced image quality. It proposes a novel architecture allowing a single model to achieve state-of-the-art performance for different quality settings by parameterizing the model with the JPEG file's quantization matrix. This eliminates the need to train a different model for each quality setting.


## Target Task

computer vision

## Content

<Abstract: >The JPEG image compression algorithm is the most popular method of image compression because of it's ability for large compression ratios. However, to achieve such high compression, information is lost. For aggressive quantization settings, this leads to a noticeable reduction in image quality. Artifact correction has been studied in the context of deep neural networks for some time, but the current methods delivering state-of-the-art results require a different model to be trained for each quality setting, greatly limiting their practical application. We solve this problem by creating a novel architecture which is parameterized by the JPEG file's quantization matrix. This allows our single model to achieve state-of-the-art performance over models trained for specific quality settings.



---

