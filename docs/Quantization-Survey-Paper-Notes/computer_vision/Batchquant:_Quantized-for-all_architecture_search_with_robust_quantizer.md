# Batchquant: Quantized-for-all architecture search with robust quantizer

## Summary

<Summary: >The paper discusses the challenges faced in single-shot quantized neural architecture search and proposed a solution called BatchQuant that allows robust quantizer formulation for fast and stable training of a compact, mixed-precision, weight-sharing supernet. The proposed method can adapt to various scenarios with varying resource constraints, making it suitable for model deployment on edge devices.


## Target Task

computer vision

## Content

<Abstract: >As the applications of deep learning models on edge devices increase at an accelerating pace, fast adaptation to various scenarios with varying resource constraints has become a crucial aspect of model deployment. As a result, model optimization strategies with adaptive configuration are becoming increasingly popular. While single-shot quantized neural architecture search enjoys flexibility in both model architecture and quantization policy, the combined search space comes with many challenges, including instability when training the weight-sharing supernet and difficulty in navigating the exponentially growing search space. Existing methods tend to either limit the architecture search space to a small set of options or limit the quantization policy search space to fixed precision policies. To this end, we propose BatchQuant, a robust quantizer formulation that allows fast and stable training of a compact, single-shot, mixed-precision, weight-sharing supernet.



---

