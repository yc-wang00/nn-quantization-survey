# Granularity-Aware Adaptation for Image Retrieval Over Multiple Tasks

## Summary

<Summary:> The Grappa approach is proposed to adapt a strong pretrained model to solve multiple retrieval tasks concurrently using only unlabeled images. It achieves this by extending the pretrained model with multiple independently trained sets of adaptors that use pseudo-label sets of different sizes to mimic different pseudo-granularities. The benchmark results show that the Grappa model improves the zero-shot performance of a state-of-the-art self-supervised learning model and in some places even performs better than a task label-aware oracle.


## Target Task

Target: Computer Vision

## Content

<Abstract:> Strong image search models should be capable of solving multiple retrieval tasks simultaneously, even if they cover different specialized domains. The proposed Grappa approach adapts a strong pretrained model to tackle multiple retrieval tasks concurrently, using only unlabeled images from the different task domains. Grappa extends the pretrained model with multiple independently trained sets of adaptors that use pseudo-label sets of different sizes, mimicking different pseudo-granularities. Results on a benchmark composed of six heterogeneous retrieval tasks show that the unsupervised Grappa model improves the zero-shot performance of a state-of-the-art self-supervised learning model, and in some places reaches or improves over a task label-aware oracle that selects the most fitting pseudo-granularity per task.



---

