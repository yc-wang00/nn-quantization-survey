# Generative low-bitwidth data free quantization

## Summary

<Summary: >The paper proposes a method called Generative Low-bitwidth Data Free Quantization (GDFQ) which aims to remove the dependency on original data for quantizing deep models. It uses a knowledge matching generator to produce fake data based on distribution information and classification boundary knowledge from a pre-trained model. The paper's experiments show that the GDFQ method effectively compresses models without the need for original data for calibration.


## Target Task

computer vision

## Content

<Abstract: >Neural network quantization is an effective way to compress deep models and improve their execution latency and energy efficiency, so that they can be deployed on mobile or embedded devices. Existing quantization methods require original data for calibration or fine-tuning to get better performance. In this paper, the authors propose a simple-yet-effective method called Generative Low-bitwidth Data Free Quantization (GDFQ) to remove the data dependence burden. The authors investigate a knowledge matching generator to produce meaningful fake data by exploiting classification boundary knowledge and distribution information in the pre-trained model. With the help of generated data, the authors can quantize a model by learning knowledge from the pre-trained model. Extensive experiments on three data sets demonstrate the effectiveness of the method.



---

