# Towards unsupervised phone and word segmentation using self-supervised vector-quantized neural networks

## Summary

Summary: The paper investigates segmenting and clustering speech into low-bitrate phone-like sequences without supervision using pretrained self-supervised vector-quantized (VQ) neural networks. Two VQ segmentation methods are proposed and tested across a range of tasks, showing that the penalized dynamic programming method performs best and outperforms a competing approach at a substantially lower bitrate.


## Target Task

Target: Speech Recognition

## Content

<Abstract: >
We investigate segmenting and clustering speech into low-bitrate phone-like sequences without supervision. We specifically constrain pretrained self-supervised vector-quantized (VQ) neural networks so that blocks of contiguous feature vectors are assigned to the same code, thereby giving a variable-rate segmentation of the speech into discrete units. Two segmentation methods are considered. In the first, features are greedily merged until a prespecified number of segments are reached. The second uses dynamic programming to optimize a squared error with a penalty term to encourage fewer but longer segments. We show that these VQ segmentation methods can be used without alteration across a wide range of tasks: unsupervised phone segmentation, ABX phone discrimination, same-different word discrimination, and as inputs to a symbolic word segmentation algorithm. The penalized dynamic programming method generally performs best. While performance on individual tasks is only comparable to the state-of-the-art in some cases, in all tasks a reasonable competing approach is outperformed at a substantially lower bitrate.



---

