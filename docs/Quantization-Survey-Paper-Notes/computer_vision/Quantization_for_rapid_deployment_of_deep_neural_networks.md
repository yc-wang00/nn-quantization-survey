# Quantization for rapid deployment of deep neural networks

## Summary

Summary: This paper introduces a method for deploying deep neural networks to energy-efficient accelerators without time-consuming fine-tuning or full datasets. The method involves converting DNNs to limited precision with channel-level distribution recognition to reduce quantization-induced accuracy loss and minimize required image samples. The results demonstrated that the proposed method can quantize 11 networks into 8-bit integer precision without fine-tuning.


## Target Task

computer vision

## Content

<Abstract:>
This paper presents a new method for rapidly deploying state-of-the-art deep neural networks (DNNs) to energy-efficient accelerators without the need for time-consuming fine tuning or the availability of full datasets. The proposed method involves converting DNNs in full precision to limited precision, which is essential in taking advantage of accelerators with reduced memory footprint and computation power. The method recognizes channel-level distribution to reduce quantization-induced accuracy loss and minimize the required image samples for profiling. The method was evaluated on eleven networks trained on the ImageNet classification benchmark and a network trained on the Pascal VOC object detection benchmark, and the results showed that the networks can be quantized into 8-bit integer precision without fine tuning.



---

