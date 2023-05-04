# Bridging the accuracy gap for 2-bit quantized neural networks (qnn)

## Summary

Summary: The paper presents techniques for quantizing a neural network by separately quantizing weights and activations resulting in an overall quantized neural network (QNN). The activation quantization technique, PACT, optimizes an activation clipping parameter during training to find the right quantization scale. The weight quantization scheme, SAWB, finds the optimal scaling factor based on the statistical characteristics of the weight distribution without an exhaustive search. The combination of PACT and SAWB results in a 2-bit QNN that achieves state-of-the-art classification accuracy on popular models and datasets.


## Target Task

computer vision

## Content

<Abstract: >Deep learning algorithms are computationally expensive, but quantization schemes have been proposed to address this issue. This paper presents novel techniques for weight and activation quantizations separately resulting in an overall quantized neural network (QNN). The activation quantization technique, PArameterized Clipping acTivation (PACT), uses an activation clipping parameter optimized during training to find the right quantization scale. The weight quantization scheme, statistics-aware weight binning (SAWB), finds the optimal scaling factor that minimizes the quantization error based on the statistical characteristics of the weight distribution without the need for an exhaustive search. The combination of PACT and SAWB results in a 2-bit QNN that achieves state-of-the-art classification accuracy comparable to full precision networks across a range of popular models and datasets.



---

