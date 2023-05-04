# Adaptive loss-aware quantization for multi-bit networks

## Summary

Summary: The proposed Adaptive Loss-aware Quantization (ALQ) method compresses deep neural networks into multi-bit networks (MBNs) with an average bitwidth below one-bit and minimal loss in inference accuracy. Unlike previous MBN quantization solutions, ALQ directly minimizes the quantization-induced error on the loss function and utilizes strategies such as adaptive bitwidth, smooth bitwidth reduction, and iterative trained quantization. Experimental results on image datasets show that ALQ outperforms state-of-the-art compressed networks.


## Target Task

computer vision

## Content

<Abstract:>
We propose Adaptive Loss-aware Quantization (ALQ) for the compression of deep neural networks into multi-bit networks (MBNs) that achieve an average bitwidth below one-bit without notable loss in inference accuracy. Unlike previous MBN quantization solutions that train a quantizer by minimizing the error to reconstruct full precision weights, ALQ directly minimizes the quantization-induced error on the loss function involving neither gradient approximation nor full precision maintenance. ALQ also exploits strategies including adaptive bitwidth, smooth bitwidth reduction, and iterative trained quantization to allow a smaller network size without loss in accuracy. Experiment results on popular image datasets show that ALQ outperforms state-of-the-art compressed networks in terms of both storage and accuracy.



---

