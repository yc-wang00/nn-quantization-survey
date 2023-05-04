# QONNX: Representing Arbitrary-Precision Quantized Neural Networks

## Summary

<Summary: >The paper presents extensions to the Open Neural Network Exchange (ONNX) format to represent low precision quantization in existing ONNX-based quantization formats using integer clipping, resulting in two new backward-compatible variants. It also introduces a novel higher-level ONNX format called Quantized ONNX (QONNX) that introduces three new operators to represent uniform quantization, enabling targeting a wider variety of platforms. Utilities for working with QONNX and examples of its usage in the FINN and hls4ml toolchains are presented. Finally, the paper introduces the QONNX model zoo to share low-precision quantized neural networks.


## Target Task

computer vision

## Content

<Abstract: >We present extensions to the Open Neural Network Exchange (ONNX) intermediate representation format to represent arbitrary-precision quantized neural networks. We first introduce support for low precision quantization in existing ONNX-based quantization formats by leveraging integer clipping, resulting in two new backward-compatible variants: the quantized operator format with clipping and quantize-clip-dequantize (QCDQ) format. We then introduce a novel higher-level ONNX format called quantized ONNX (QONNX) that introduces three new operators— Quant, BipolarQuant, and Trunc—in order to represent uniform quantization. By keeping the QONNX IR high-level and flexible, we enable targeting a wider variety of platforms. We also present utilities for working with QONNX, as well as examples of its usage in the FINN and hls4ml toolchains. Finally, we introduce the QONNX model zoo to share low-precision quantized neural networks. Index Terms —quantized neural network, intermediate representation, FPGA.



---

