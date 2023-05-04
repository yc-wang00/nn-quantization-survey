# Optimal quantization using scaled codebook

## Summary

<Summary:>
The paper focuses on the problem of quantizing scalar data points with a fixed codebook containing K entries that can be rescaled. The authors derive an algorithm that is guaranteed to find the optimal quantization parameters for any fixed codebook regardless of data distribution. The algorithm has a time complexity of O(NKlogK). The authors also apply their algorithm to various neural network quantization problems and show its effectiveness.


## Target Task

computer vision

## Content

<Abstract:>
We study the problem of quantizing Nsorted, scalar data points with a fixed codebook containing K entries that are allowed to be rescaled. By studying the properties of the optimal quantizer, we derive an O(NKlogK) algorithm that is guaranteed to find the optimal quantization parameters for any fixed codebook regardless of data distribution. We apply our algorithm to synthetic and real-world neural network quantization problems and demonstrate the effectiveness of our approach.



---

