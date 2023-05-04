# Granularity-Aware Adaptation for Image Retrieval Over Multiple Tasks

## Summary

<Summary: > The paper proposes an approach called Grappa that adapts a pre-trained model to solve multiple image retrieval tasks concurrently, using only unlabeled images from different task domains. The model is extended with multiple sets of adaptors that use pseudo-label sets of different sizes, which are reconciled into a unified model using fusion layers. The authors show that Grappa improves the zero-shot performance of a state-of-the-art self-supervised learning model and can match or outperform a task label-aware oracle.


## Target Task

computer vision

## Content

<Abstract: >Strong image search models can be learned for a specific domain if labeled images of that domain are available. However, a practical visual search model should be versatile enough to solve multiple retrieval tasks simultaneously, even if those cover very different specialized domains. We propose Grappa, an approach that adapts a strong pretrained model to tackle multiple retrieval tasks concurrently, using only unlabeled images from the different task domains. We extend the pretrained model with multiple independently trained sets of adaptors that use pseudo-label sets of different sizes, effectively mimicking different pseudo-granularities. We reconcile all adaptor sets into a single unified model suited for all retrieval tasks by learning fusion layers that we guide by propagating pseudo-granularity attentions across neighbors in the feature space. Results on a benchmark composed of six heterogeneous retrieval tasks show that the unsupervised Grappa model improves the zero-shot performance of a state-of-the-art self-supervised learning model, and in some places reaches or improves over a task label-aware oracle that selects the most fitting pseudo-granularity per task.



---

