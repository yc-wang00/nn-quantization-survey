# Dynamic network quantization for efficient video inference

## Summary

Summary: This paper presents a dynamic network quantization framework that selects optimal precision for each frame of a video clip conditioned on the input for efficient video recognition. The proposed approach trains two networks in parallel, a recognition network and a lightweight network, to achieve both competitive performance and resource efficiency. The experiments on benchmark datasets showed significant savings in computation and memory usage while outperforming existing state-of-the-art methods.


## Target Task

computer vision

## Content

<Abstract: >Deep convolutional networks have recently achieved great success in video recognition, yet their practical realization remains a challenge due to the large amount of computational resources required to achieve robust recognition. Motivated by the effectiveness of quantization for boosting efficiency, in this paper, we propose a dynamic network quantization framework, that selects optimal precision for each frame conditioned on the input for efficient video recognition. Specifically, given a video clip, we train a very lightweight network in parallel with the recognition network, to produce a dynamic policy indicating which numerical precision to be used per frame in recognizing videos. We train both networks effectively using standard backpropagation with a loss to achieve both competitive performance and resource efficiency required for video recognition. Extensive experiments on four challenging diverse benchmark datasets demonstrate that our proposed approach provides significant savings in computation and memory usage while outperforming the existing state-of-the-art methods. Project page: https://cs-people.bu.edu/sunxm/VideoIQ/project.html.



---

