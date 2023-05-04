# A white paper on neural network quantization

## Summary

<Summary: >The paper introduces methods for mitigating the impact of quantization noise on neural network performance while reducing power and latency. Two classes of algorithms, Post-Training Quantization (PTQ) and Quantization-Aware-Training (QAT), are considered, with PTQ requiring no re-training or labelled data and QAT requiring fine-tuning and access to labelled training data. The paper provides tested pipelines based on existing literature and experimental results for achieving state-of-the-art performance for common deep learning models and tasks.


## Target Task

computer vision

## Content

<Abstract: >While neural networks have advanced the frontiers in many applications, they often come at a high computational cost. Reducing the power and latency of neural network inference is key if we want to integrate modern networks into edge devices with strict power and compute requirements. Neural network quantization is one of the most effective ways of achieving these savings but the additional noise it induces can lead to accuracy degradation.
In this white paper, we introduce state-of-the-art algorithms for mitigating the impact of quantization noise on the network’s performance while maintaining low-bit weights and activations. We start with a hardware motivated introduction to quantization and then consider two main classes of algorithms: Post-Training Quantization (PTQ) and Quantization-Aware-Training (QAT). PTQ requires no re-training or labelled data and is thus a lightweight push-button approach to quantization. In most cases, PTQ is sufficient for achieving 8-bit quantization with close to floating-point accuracy. QAT requires fine-tuning and access to labeled training data but enables lower bit quantization with competitive results. For both solutions, we provide tested pipelines based on existing literature and extensive experimentation that lead to state-of-the-art performance for common deep learning models and tasks.



---

