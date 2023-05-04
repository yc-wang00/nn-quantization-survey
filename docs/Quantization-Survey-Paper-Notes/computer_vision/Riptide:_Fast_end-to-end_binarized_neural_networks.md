# Riptide: Fast end-to-end binarized neural networks

## Summary

<Summary: >This paper explores the challenges in achieving high performance using binarized neural networks and proposes solutions to overcome them. The proposed techniques show speedups ranging from 4-12 times and demonstrate a 6.3x speedup over a standard VGGNet variant with state-of-the-art accuracy. The authors highlight the importance of missing implementations for certain operations and carefully scheduled library support for binarized linear algebra operations to achieve such performance gains.


## Target Task

computer vision

## Content

<Abstract: >Binarized neural networks have attracted much recent attention due to their promise of making convolutional neural networks fast and compact. However, these benefits have proven hard to realize in practice. In this paper, we identify the underlying barriers to high performance and propose solutions ranging from missing implementations for certain operations to carefully scheduled library support for binarized linear algebra operations. The combination of these innovations allows us to report the first measured end-to-end speedups for binarized networks. For instance, we show a 6.3x speedup over a standard VGGNet variant at state-of-the-art (64.2% for top-1 binarized classification of ImageNet) accuracy. More broadly, speedups range from 4-12x and the techniques we propose are crucial to achieving them.



---

