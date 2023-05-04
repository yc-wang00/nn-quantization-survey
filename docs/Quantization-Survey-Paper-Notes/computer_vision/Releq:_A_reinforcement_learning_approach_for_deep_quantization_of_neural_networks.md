# Releq: A reinforcement learning approach for deep quantization of neural networks

## Summary

<Summary: >This paper proposes a systematic approach to automating the process of deep quantization for neural networks to minimize computational and storage costs while preserving accuracy. The approach uses a deep reinforcement learning framework called RELEQ. The proposed approach provides a general solution for quantization of a variety of deep networks with the potential to achieve a speedup of up to 2.2x and reduce energy consumption for hardware and custom DNN accelerators compared to 8-bit runs.


## Target Task

computer vision

## Content

<Abstract: > Deep Neural Networks (DNNs) require massive amounts of computation resources in inference tasks for computer vision applications. Quantization can significantly reduce DNN computation and storage by decreasing the bitwidth of network encodings. Recent research affirms that carefully selecting the quantization levels for each layer can preserve the accuracy while pushing the bitwidth below eight bits. However, without manual effort, this deep quantization can lead to a significant loss in accuracy. We proposed a systematic approach to tackle this problem, by automating the process of discovering the quantization levels through an end-to-end deep reinforcement learning framework (RELEQ). We show how RELEQ can balance speed and quality, and provide an asymmetric general solution for quantization of a large variety of deep networks that virtually preserve the accuracy while minimizing the computation and storage cost. With these DNNs, RELEQ enables conventional hardware to achieve a 2.2x speedup over 8-bit execution, and a custom DNN accelerator achieves a 2.0x speedup and energy reduction compared to 8-bit runs. These encouraging results mark RELEQ as the initial step towards automating the deep quantization of neural networks.



---

