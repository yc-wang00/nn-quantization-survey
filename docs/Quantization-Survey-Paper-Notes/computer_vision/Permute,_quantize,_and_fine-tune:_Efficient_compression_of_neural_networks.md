# Permute, quantize, and fine-tune: Efficient compression of neural networks

## Summary

Summary: The paper proposes a technique named PQF which is used to compress large neural networks for deployment in resource-constrained platforms. PQF uses rate-distortion theory to search for permutations of the network weights that yield functionally equivalent, easier-to-quantize networks. PQF shows promising results in reducing the gap with the uncompressed model in image classification, object detection, and segmentation tasks.


## Target Task

computer vision

## Content

<Abstract: >
Compressing large neural networks for deployment in resource-constrained platforms is crucial. Vector quantization (VQ) has emerged as an efficient technique that compresses multiple parameters into a single code. However, determining which parameters to compress jointly poses a problem. In this paper, we propose Permute, Quantize and Fine-tune (PQF), which leverages rate-distortion theory to search for permutations of the network weights that yield functionally equivalent, easier-to-quantize networks. PQF searches for permutations, codes and codebooks that minimize the reconstruction error of the network weights and uses gradient-based optimization to recover the accuracy of the uncompressed network. PQF shows promising results, reducing the gap with the uncompressed model by 40 to 70% w.r.t. the current state of the art, in image classification, object detection, and segmentation tasks. All the experiments can be reproduced using the code provided in https://github.com/uber-research/permute-quantize-finetune.



---

