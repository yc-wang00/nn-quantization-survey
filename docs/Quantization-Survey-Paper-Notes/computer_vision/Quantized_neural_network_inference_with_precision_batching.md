# Quantized neural network inference with precision batching

## Summary

<Summary: >The paper presents PrecisionBatching, a quantized inference algorithm that speeds up neural network execution on traditional hardware platforms at low bitwidths without retraining or recalibration. It decomposes a neural network into individual bitlayers and accumulates them using fast 1-bit operations while maintaining activations in full precision. PrecisionBatching facilitates quantized inference at low bitwidths (<8bits) and enables traditional hardware platforms to realize inference speedups at finer granularity of quantization. It also allows accuracy and speedup tradeoffs at runtime by exposing the number of bitlayers to accumulate as a tunable parameter. The algorithm yields end-to-end speedups of over 8x on a GPU within a <1% error margin of the full precision baseline, outperforming traditional 8-bit quantized inference by over 1.5-2x at the same error tolerance across several applications and neural network architectures.


## Target Task

computer vision

## Content

<Abstract: >We present PrecisionBatching, a quantized inference algorithm for speeding up neural network execution on traditional hardware platforms at low bitwidths without the need for retraining or recalibration. PrecisionBatching decomposes a neural network into individual bitlayers and accumulates them using fast 1-bit operations while maintaining activations in full precision. PrecisionBatching not only facilitates quantized inference at low bitwidths (<8bits) without the need for retraining/recalibration, but also 1) enables traditional hardware platforms the ability to realize inference speedups at a finer granularity of quantization (e.g: 1-16 bit execution) and 2) allows accuracy and speedup tradeoffs at runtime by exposing the number of bitlayers to accumulate as a tunable parameter. Across a variety of applications (MNIST, language modeling, natural language inference) and neural network architectures (fully connected, RNN, LSTM), Precision-Batching yields end-to-end speedups of over 8x on a GPU within a <1% error margin of the full precision baseline, outperforming traditional 8-bit quantized inference by over 1.5-2x at the same error tolerance.



---

