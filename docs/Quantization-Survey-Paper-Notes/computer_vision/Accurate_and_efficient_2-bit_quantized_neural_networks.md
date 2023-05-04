# Accurate and efficient 2-bit quantized neural networks

## Summary

<Summary: > The paper proposes a novel technique for weight and activation quantization resulting in a quantized neural network. The activation quantization method, PACT, optimizes the activation clipping parameter during training to find the right quantization scale. The weight quantization method, SAWB, finds the optimal scaling factor that minimizes the quantization error based on weight distribution statistics without an exhaustive search. The technique achieves state-of-the-art classification accuracy comparable to full precision networks, using a 2-bit QNN on popular models and datasets, and provides insight for quantization in the presence of shortcut connections.


## Target Task

computer vision

## Content

<Abstract: >Deep learning algorithms achieve high classification accuracy at the expense of significant computation cost. In order to reduce this cost, several quantization schemes have gained attention recently with some focusing on weight quantization, and others focusing on quantizing activations. This paper proposes novel techniques that individually target weight and activation quantizations resulting in an overall quantized neural network (QNN). Our activation quantization technique, PArameterized Clipping acTivation (PACT), uses an activation clipping parameter that is optimized during training to find the right quantization scale. Our weight quantization scheme, statistics-aware weight binning (SAWB), finds the optimal scaling factor that minimizes the quantization error based on the statistical characteristics of weight distribution without the need for an exhaustive search. Furthermore, we provide an innovative insight for quantization in the presence of shortcut connections, which motivates the use of high-precision for the shortcuts. The combination of PACT and SAWB results in a 2-bit QNN that achieves state-of-the-art classification accuracy (comparable to full precision networks) across a range of popular models and datasets.



---

