# Information Bottleneck: Exact Analysis of (Quantized) Neural Networks

## Summary

<Summary: > The study examines the impact of the information bottleneck principle on deep neural networks through mutual information between hidden layers and input and output. Different methods of binning result in divergent outcomes. The study monitors the dynamics of quantized neural networks, with exact computation of mutual information, to measure information flow without measurement errors. The study confirms initial IB results without any artifacts of binning, with the comprehension phase depending on the type of activation function, but the compression phase might not be seen in certain networks.


## Target Task

computer vision

## Content

<Abstract: >The information bottleneck (IB) principle has been suggested as a way to analyze deep neural networks. The learning dynamics are studied by inspecting the mutual information (MI) between the hidden layers and the input and output. Our study confirms that different ways of binning when computing the MI lead to qualitatively different results, either supporting or refusing IB conjectures. To resolve the controversy, we study the IB principle in settings where MI is non-trivial and can be computed exactly. We monitor the dynamics of quantized neural networks, that is, we discretize the whole deep learning system so that no approximation is required when computing the MI. This allows us to quantify the information flow without measurement errors. In this setting, we observed a fitting phase for all layers and a compression phase for the output layer in all experiments; the compression in the hidden layers was dependent on the type of activation function. Our study shows that the initial IB results were not artifacts of binning when computing the MI. However, the critical claim that the compression phase may not be observed for some networks also holds true.



---

