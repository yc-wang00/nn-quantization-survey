# Qnet: an adaptive quantization table generator based on convolutional neural network

## Summary

Summary: The paper proposes a CNN-based optimal quantization table generator called QNet, which directly generates an adaptive quantization table by fusing frequency and spatial domain information of more than 10,000 images. It also presents a classification network to train to indicate the optimal quantization table for each image, improving compression performance and computational efficiency. The proposed method outperforms state-of-the-art methods and is computationally efficient, taking only a few milliseconds to process an image on a single CPU core.


## Target Task

computer vision

## Content

<Abstract: > The paper proposes a Convolutional Neural Network (CNN) based optimal quantization table generator called QNet, to obtain an image-adaptive quantization table for a JPEG image in a standard-compliant way. The proposed method extracts and fuses the frequency and spatial domain information of more than 10,000 images to directly generate an adaptive quantization table. Additionally, the paper presents a method to train a classification network to indicate the optimal quantization table for each image, further improving the compression performance and computational efficiency. Experimental results show that the proposed method outperforms state-of-the-art methods in terms of Peak Signal-to-Noise Ratio (PSNR) gains of nearly 1.2 and 1.4 dB, and improvements of 0.4% and 0.54% in Structural Similarity Index Measurement (SSIM), respectively. Moreover, the proposed method is computationally efficient, taking only 15 and 6.25 milliseconds, respectively, to process a 768 × 512 image on a single CPU core at 3.20 GHz.



---

