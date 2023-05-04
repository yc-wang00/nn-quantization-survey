# Towards unsupervised phone and word segmentation using self-supervised vector-quantized neural networks

## Summary

<Summary:> The paper introduces a method for segmenting and clustering speech into low-bitrate phone-like sequences without supervision using pretrained self-supervised vector-quantized (VQ) neural networks. The method assigns blocks of contiguous feature vectors to the same code, resulting in variable-rate segmentation of speech into discrete units for unsupervised phone segmentation, ABX phone discrimination, same-different word discrimination, and as inputs to a symbolic word segmentation algorithm. The penalized dynamic programming method performs the best. The proposed method outperforms the state-of-the-art in some cases at a substantially lower bitrate.


## Target Task

speech recognition

## Content

<Abstract: > We investigate segmenting and clustering speech into low-bitrate
phone-like sequences without supervision. We speciﬁcally con-
strain pretrained self-supervised vector-quantized (VQ) neural
networks so that blocks of contiguous feature vectors are as-
signed to the same code, thereby giving a variable-rate segmenta-
tion of the speech into discrete units. Two segmentation methods
are considered. In the ﬁrst, features are greedily merged until a
prespeciﬁed number of segments are reached. The second uses
dynamic programming to optimize a squared error with a penalty
term to encourage fewer but longer segments. We show that these
VQ segmentation methods can be used without alteration across
a wide range of tasks: unsupervised phone segmentation, ABX
phone discrimination, same-different word discrimination, and
as inputs to a symbolic word segmentation algorithm. The pe-
nalized dynamic programming method generally performs best.
While performance on individual tasks is only comparable to the
state-of-the-art in some cases, in all tasks a reasonable competing
approach is outperformed at a substantially lower bitrate.



---

