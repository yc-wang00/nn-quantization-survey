# Product quantization network for fast visual search

## Summary

Summary: The paper introduces product quantization network (PQN), a neural network layer that enables the construction of a discriminative and compact image representation for fast and accurate image retrieval. The network also extends to residual product quantization network (RPQN) and temporal product quantization network (TPQN), which achieve higher accuracy and speed up video retrieval by exploiting temporal consistency respectively. The proposed method is experimented on multiple public benchmark datasets and shows state-of-the-art performance in fast image and video retrieval.


## Target Task

computer vision

## Content

<Abstract:>
Product quantization has been widely used in fast image retrieval due to its effectiveness of coding high-dimensional visual features. By constructing the approximation function, we extend the hard-assignment quantization to soft-assignment quantization. Thanks to the differentiable property of the soft-assignment quantization, the product quantization operation can be integrated as a layer in a convolutional neural network, constructing the proposed product quantization network (PQN). Meanwhile, by extending the triplet loss to the asymmetric triplet loss, we directly optimize the retrieval accuracy of the learned representation based on asymmetric similarity measurement. Utilizing PQN, we can learn a discriminative and compact image representation in an end-to-end manner, which further enables a fast and accurate image retrieval. By revisiting residual quantization, we further extend the proposed PQN to residual product quantization network (RPQN). Benefited from the residual learning triggered by residual quantization, RPQN achieves a higher accuracy than PQN using the same computation cost. Moreover, we extend PQN to temporal product quantization network (TPQN) by exploiting temporal consistency in videos to speed up the video retrieval. It integrates frame-wise feature learning, frame-wise features aggregation, and video-level feature quantization in a single neural network. Comprehensive experiments conducted on multiple public benchmark datasets demonstrate the state-of-the-art performance of the proposed PQN, RPQN, and TPQN in fast image and video retrieval.




---

