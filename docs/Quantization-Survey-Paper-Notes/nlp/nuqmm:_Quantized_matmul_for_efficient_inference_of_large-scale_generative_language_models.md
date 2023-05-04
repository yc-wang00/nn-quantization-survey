# nuqmm: Quantized matmul for efficient inference of large-scale generative language models

## Summary

Summary: The paper proposes an efficient inference framework for large-scale generative language models by quantizing weights using a non-uniform quantization method and accelerating quantized matrix multiplications with the proposed nuQmm kernel. This reduces the model size and latency of inference for large LMs, allowing a wide trade-off between compression ratio and accuracy. This is achieved by reducing the minimum required number of GPUs through high compression ratios using low-bit quantization.


## Target Task

nlp

## Content

<Abstract: The recent advance of self-supervised learning associated with the Transformer architecture enables natural language processing (NLP) to exhibit extremely low perplexity. Such powerful models demand ever-increasing model size and, thus, large amounts of computations and memory footprints. In this paper, we propose an efficient inference framework for large-scale generative language models. As the key to reducing model size, we quantize weights by a non-uniform quantization method. Then, quantized matrix multiplications are accelerated by our proposed kernel, called nuQmm, which allows a wide trade-off between compression ratio and accuracy. Our proposed nuQmm reduces the latency of not only each GPU but also the entire inference of large LMs because a high compression ratio (by low-bit quantization) mitigates the minimum required number of GPUs.>



---

