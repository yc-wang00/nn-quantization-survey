# Deep image compression with iterative non-uniform quantization

## Summary

<Summary: > The paper proposes a novel iterative non-uniform quantization scheme for deep image compression that optimizes the non-uniform quantizer and the encoder-decoder alternatively, resulting in improved PSNR index and more flexibility in compressing complex image structures than existing deep compressors and JPEG2000. However, the non-differentiable nature of quantizers limits their performance when using deep convolutional neural networks (CNNs) in image compression.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose an iterative non-uniform quantization scheme for deep image compression. The scheme alternately optimizes the non-uniform quantizer and the encoder-decoder of the compression system. The non-uniform quantizer is optimized based on the features’ distribution while the encoder-decoder is updated by fixing the quantizer. This method improves the PSNR index and allows for more flexibility in compressing complex image structures than existing deep compressors and JPEG2000. Although deep convolutional neural networks (CNNs) have led to breakthroughs in image compression, the non-differentiable nature of quantizers limits their performance.



---

