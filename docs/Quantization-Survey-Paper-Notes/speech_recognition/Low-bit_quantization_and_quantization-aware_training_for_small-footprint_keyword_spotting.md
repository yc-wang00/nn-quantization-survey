# Low-bit quantization and quantization-aware training for small-footprint keyword spotting

## Summary

<Summary: > The paper proposes a new method called dynamic quantization to reduce memory and computation footprint of deep neural network (DNN) based Keyword Spotters (KWS). Dynamic quantization performs column-wise quantization of DNN weight matrices using each column's exact individual min-max range. The paper also proposes a quantization-aware training approach that incorporates quantization errors into the KWS model during training. These approaches together achieve accuracy close to full precision models while reducing the models' on-device memory footprint up to 80%.


## Target Task

speech recognition

## Content

<Abstract: > In this paper, the authors propose a novel method for reducing the memory and computational footprint of deep neural network (DNN) based keyword spotters (KWS). This method, called dynamic quantization, performs column-wise quantization of DNN weight matrices using each column's exact individual min-max range. Additionally, the authors propose a quantization-aware training approach that incorporates quantization errors into the KWS model during training. Together, these approaches significantly improve the performance of KWS in 4-bit and 8-bit quantized precision, achieving end-to-end accuracy close to that of full precision models while reducing the models' on-device memory footprint by up to 80%.



---

