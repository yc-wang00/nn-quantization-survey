# Low-bit quantization of recurrent neural network language models using alternating direction methods of multipliers

## Summary

<Summary: > The paper proposes a method for training quantized RNNLMs using ADMM for low-bit compression. The method adjusts the balance between compression and model performance using tied low-bit quantization tables. The experiments show that the proposed ADMM quantization achieved up to 31 times model compression with faster convergence compared to baseline binarized RNNLM quantization.


## Target Task

nlp

## Content

<Abstract: >The paper presents a novel method for training quantized Recurrent neural network language models (RNNLMs) using alternating direction methods of multipliers (ADMM) to achieve extremely low-bit compression. The proposed method can flexibly adjust the trade-off between compression rate and model performance using tied low-bit quantization tables. The experiments on Penn Treebank (PTB), and Switchboard (SWBD) suggest the proposed ADMM quantization achieved a model size compression factor of up to 31 times over the full precision baseline RNNLMs, with faster convergence of 5 times in model training over the baseline binarized RNNLM quantization.



---

