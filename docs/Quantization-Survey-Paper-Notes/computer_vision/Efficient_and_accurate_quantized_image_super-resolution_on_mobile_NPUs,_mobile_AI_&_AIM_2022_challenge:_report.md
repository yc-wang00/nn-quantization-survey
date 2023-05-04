# Efficient and accurate quantized image super-resolution on mobile NPUs, mobile AI & AIM 2022 challenge: report

## Summary

Summary: The paper discusses the Mobile AI challenge that focuses on designing an efficient quantized image super-resolution solution compatible with low-power mobile NPUs. The participants trained INT8 models on the DIV2K dataset and evaluated their models on the Synaptics VS680 Smart Home board with a dedicated edge NPU capable of accelerating quantized neural networks. All proposed solutions in the challenge are fully compatible with the NPU and can reconstruct Full HD resolution images at up to 60 FPS rate. A detailed description of all models is provided in the paper.


## Target Task

computer vision

## Content

<Abstract: > Image super-resolution is a common task on mobile and IoT devices, where one often needs to upscale and enhance low-resolution images and video frames. While numerous solutions have been proposed for this problem in the past, they are usually not compatible with low-power mobile NPUs having many computational and memory constraints. In this Mobile AI challenge, we address this problem and propose the participants to design an efficient quantized image super-resolution solution that can demonstrate a real-time performance on mobile NPUs. The participants were provided with the DIV2K dataset and trained INT8 models to do a high-quality 3X image upscaling. The runtime of all models was evaluated on the Synaptics VS680 Smart Home board with a dedicated edge NPU capable of accelerating quantized neural networks. All proposed solutions are fully compatible with the above NPU, demonstrating an up to 60 FPS rate when reconstructing Full HD resolution images. A detailed description of all models developed in the challenge is provided in this paper.



---

