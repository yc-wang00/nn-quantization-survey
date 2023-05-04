# What do compressed deep neural networks forget?

## Summary

<Summary: > The paper discusses the significance of deep neural network pruning and quantization techniques in achieving high levels of compression without significant degradation to test set accuracy. It is suggested that although the models have comparable top-line performance metrics, there are considerable differences in behavior for a small subset of data points that are impacted by sparsity. The paper provides a formal framework to audit the disparate harm incurred by compression, and highlights the need to understand this impact, considering the widespread deployment of compressed models in the wild.


## Target Task

computer vision

## Content

<Abstract: > 
Deep neural network pruning and quantization techniques have demonstrated it is possible
to achieve high levels of compression with surprisingly little degradation to test set accuracy.
However, this measure of performance conceals signiﬁcant differences in how different
classes and images are impacted by model compression techniques. We ﬁnd that models
with radically different numbers of weights have comparable top-line performance metrics
but diverge considerably in behavior on a narrow subset of the dataset. This small subset of
data points, which we term Pruning Identiﬁed Exemplars (PIEs), are systematically more
impacted by the introduction of sparsity. Our work is the ﬁrst to provide a formal framework
for auditing the disparate harm incurred by compression and a way to quantify the trade-
offs involved. An understanding of this disparate impact is critical given the widespread
deployment of compressed models in the wild.



---

