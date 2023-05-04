# On the quantization of recurrent neural networks

## Summary

<Summary: >The paper talks about the challenges related to integer quantization of neural networks that reduce memory consumption and ML execution time, but may negatively impact the model's quality. The authors present an integer-only quantization strategy for LSTM neural network topologies that is accurate, efficient, and uses 8-bit integer weights and mostly 8-bit activations. The strategy targets various hardware and leverages instruction sets available in CPU architectures and neural accelerators. The paper discusses various factors that influence quantization, including representations in the integer domain, precision used for computation results, and conversion of intermediate results for efficient computation.


## Target Task

speech recognition

## Content

<Abstract: >Integer quantization of neural networks is an important technique that reduces memory consumption and machine learning (ML) execution time. However, quantization may negatively affect the model's quality. Therefore, devising quantization strategies that preserve the quality of the original neural networks while providing its benefits is a challenging area of research. In this work, the authors present an integer-only quantization strategy for Long Short-Term Memory (LSTM) neural network topologies, which are the foundation of many production ML systems. This quantization strategy is accurate, efficient, and fast to execute, utilizing 8-bit integer weights and mostly 8-bit activations. Additionally, it is able to target various hardware by leveraging instruction sets available in common CPU architectures and available neural accelerators. The researchers address the challenging problem of fully quantizing RNNs, particularly LSTM topologies, which are extensively employed in state-of-the-art production systems such as speech recognition, text translation, and text-to-speech, among others. They discuss various factors that influence quantization, including representations in the integer domain, the precision used to represent the results of computations, and how the intermediate results are converted for subsequent computations to occur efficiently.



---

