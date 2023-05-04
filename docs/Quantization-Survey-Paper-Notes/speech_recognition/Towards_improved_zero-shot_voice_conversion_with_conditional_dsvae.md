# Towards improved zero-shot voice conversion with conditional dsvae

## Summary

Summary: The paper proposes an enhanced framework for zero-shot non-parallel voice conversion utilizing disentangled sequential variational autoencoder (DSV AE) for information decomposition. The authors suggest that disentangling content and speaking style is crucial for zero-shot non-parallel voice conversion. The proposed conditional DSV AE (C-DSV AE) model uses content bias as a condition to reshape the content embedding for better content embeddings with more phonetic information, resulting in better phoneme classification accuracy, stabilized vocalization, and improved zero-shot VC performance compared to the DSV AE baseline.


## Target Task

speech recognition

## Content

<Abstract:>
The paper proposes an improved zero-shot non-parallel voice conversion framework with disentangled sequential variational autoencoder (DSV AE) as the backbone for information decomposition. The authors suggest that the disentangling of content and speaking style information is essential for zero-shot non-parallel voice conversion. The proposed conditional DSV AE (C-DSV AE) model enables the use of content bias as a condition to the prior modeling and reshapes the content embedding sampled from the posterior distribution for a better content embedding with more phonetic information preserved. The paper demonstrates that content embeddings derived from the C-DSV AE overcome the randomness and achieve a much better phoneme classification accuracy, a stabilized vocalization, and a better zero-shot VC performance compared to the competitive DSV AE baseline.



---

