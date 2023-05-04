# Vector-quantized image modeling with improved VQGAN

## Summary

<Summary: >The paper explores the Vector-quantized Image Modeling (VIM) approach that includes pretraining a Transformer to predict rasterized image tokens autoregressively. The learning of discrete image tokens is done from a learned Vision-Transformer-based VQGAN. The proposed method achieves Inception Score (IS) of 175.1 and Fréchet Inception Distance (FID) of 4.17 on ImageNet at 256x256 resolution, which is a significant improvement over vanilla VQGAN. The pretrained Transformer by averaging intermediate features performs well and outperforms iGPT-XL.


## Target Task

computer vision

## Content

<Abstract: >We explore a Vector-quantized Image Modeling (VIM) approach that includes pretraining a Transformer to predict rasterized image tokens autoregressively. The discrete image tokens are encoded from a learned Vision-Transformer-based VQGAN (ViT-VQGAN). Multiple improvements to vanilla VQGAN from architecture to codebook learning are proposed, resulting in better efficiency and reconstruction fidelity. The improved ViT-VQGAN further improves vector-quantized image modeling tasks, including unconditional, class-conditioned image generation, and unsupervised representation learning. When trained on ImageNet at 256x256 resolution, the proposed method achieves Inception Score (IS) of 175.1 and Fréchet Inception Distance (FID) of 4.17, a significant improvement over vanilla VQGAN. Pretrained Transformer by averaging intermediate features also performs well and outperforms iGPT-XL.



---

