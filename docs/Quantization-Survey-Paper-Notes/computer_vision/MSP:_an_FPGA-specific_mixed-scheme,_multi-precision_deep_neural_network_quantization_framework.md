# MSP: an FPGA-specific mixed-scheme, multi-precision deep neural network quantization framework

## Summary

<Summary: >The paper discusses the need to deploy deep learning models onto edge devices with limited computing and storage resources. This has led to the usage of model compression techniques, primarily DNN quantization. The paper proposes a mixed-scheme DNN quantization method that incorporates both linear and non-linear number systems to boost the utilization of LUTs and DSPs on an FPGA. It also uses a quantization method that supports multiple precisions along the intra-layer dimension, which can uniform the hardware configurations for different layers to reduce computation overhead while preserving model accuracy.


## Target Task

computer vision

## Content

<Abstract: >With the tremendous success of deep learning, there exists imminent need to
deploy deep learning models onto edge devices. To tackle the limited com-
puting and storage resources in edge devices, model compression techniques
have been widely used to trim deep neural network (DNN) models for on-
device inference execution. This paper targets the commonly used FPGA
(eld programmable gate array) devices as the hardware platforms for DNN
edge computing. We focus on the DNN quantization as the main model com-
pression technique, since DNN quantization has been of great importance for
the implementations of DNN models on the hardware platforms. The nov-
elty of this work comes in twofold: (i) We propose a mixed-scheme DNN
quantization method that incorporates both the linear and non-linear num-
ber systems for quantization, with the aim to boost the utilization of the
heterogeneous computing resources, i.e., LUTs (look up tables) and DSPs
(digital signal processors) on an FPGA. Note that all the existing (single-
scheme) quantization methods can only utilize one type of resources (either
LUTs or DSPs for the MAC (multiply-accumulate) operations in deep learn-
ing computations. (ii) We use a quantization method that supports multiple
precisions along the intra-layer dimension, while the existing quantization
methods apply multi-precision quantization along the inter-layer dimension.
The intra-layer multi-precision method can uniform the hardware congura-
tions for dierent layers to reduce computation overhead and at the same
time preserve the model accuracy as the inter-layer approach.



---

