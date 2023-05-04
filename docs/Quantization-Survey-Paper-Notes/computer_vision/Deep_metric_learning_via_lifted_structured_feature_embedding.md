# Deep metric learning via lifted structured feature embedding

## Summary

Summary: The paper presents an algorithm for learning the metric distance between pairs of examples in neural network training. It describes a method for lifting the vector of pairwise distances within a training batch to a matrix of pairwise distances, enabling the algorithm to optimize a novel structured prediction objective. The authors also collected a dataset of 120k images of online products for metric learning and experimented with the GoogLeNet network. Results show significant improvement over existing deep feature embedding methods on all tested embedding sizes.


## Target Task

computer vision

## Content

<Abstract: Learning the distance metric between pairs of examples is of great importance for learning and visual recognition. With the remarkable success from the state of the art convolutional neural networks, recent works [1,31] have shown promising results on discriminatively training the networks to learn semantic feature embeddings where similar examples are mapped close to each other and dissimilar examples are mapped farther apart. In this paper, we describe an algorithm for taking full advantage of the training batches in the neural network training by lifting the vector of pairwise distances within the batch to the matrix of pairwise distances. This step enables the algorithm to learn the state of the art feature embedding by optimizing a novel structured prediction objective on the lifted problem. Additionally, we collected Stanford Online Products dataset: 120k images of 23k classes of online products for metric learning. Our experiments on the CUB-200-2011 [37], CARS196 [19], and Stanford Online Products datasets demonstrate significant improvement over existing deep feature embedding methods on all experimented embedding sizes with the GoogLeNet [33] network.>



---

