# Anchor-based plain net for mobile image super-resolution

## Summary

<Summary: >The paper proposes an efficient 8-bit quantization architecture for image super-resolution on mobile devices called anchor-based plain net (ABPN) that outperforms other quantized models. The authors focus on creating a general SISR network that is beneficial to 8-bit quantization and adopt a quantization-aware training strategy to further boost performance. They also research meta-node latency on mobile hardware to determine what kind of architecture is most effective for INT8 quantization.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors propose an efficient architecture for 8-bit quantization that can be deployed on mobile devices for image super-resolution. They conducted experiments on lightweight SR architectures to determine portable operations that can be utilized, and propose anchor-based plain net (ABPN) which outperforms quantized FSRCNN by nearly 2dB in terms of PSNR. The model satisfies realistic needs by adopting quantization-aware training strategy to further boost the performance. The authors' focus is on creating a general SISR network architecture that is beneficial to 8-bit quantization. Their main contribution is researching meta-node latency on mobile hardware and digging deeper into what kind of architecture can really make sense to INT8 quantization.



---

