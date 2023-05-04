# [PDF][PDF] Releq: an automatic reinforcement learning approach for deep quantization of neural networks

## Summary

Summary: The paper discusses deep quantization and its ability to reduce computation and storage costs in deep neural networks. However, manually selecting quantization levels can lead to accuracy loss. To address this challenge, the paper proposes an automatic end-to-end deep reinforcement learning framework called ReLeQ, which balances speed and quality and can achieve a speedup of up to 2.2x over 8-bit execution with virtually preserved accuracy, making it a step towards automating deep quantization of neural networks.


## Target Task

computer vision

## Content

<Abstract:>
Deep neural networks (DNNs) are computation intensive and require significant amounts of resources for inference tasks in computer vision. Quantization can reduce storage and computation costs by decreasing the bitwidth of network encodings. Recent research has shown that selecting the quantization levels for each layer can preserve accuracy while pushing the bitwidth below eight bits. However, this deep quantization can lead to significant accuracy loss without manual effort. Deep quantization opens a large hyper-parameter space and becomes a major challenge. This paper proposes an automatic end-to-end deep reinforcement learning framework (ReLeQ) for discovering the quantization levels. ReLeQ balances speed and quality and provides a solution for quantization of a large variety of deep networks while minimizing computation and storage cost. Results show that ReLeQ can achieve a speedup of up to 2.2x over 8-bit execution, with virtually preserved accuracy, making it the initial step towards automating the deep quantization of neural networks.



---

