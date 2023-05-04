# Compressing deep convolutional networks using vector quantization

## Summary

<Summary: >The paper investigates information theoretical vector quantization methods for compressing the parameters of CNNs to overcome the storage issue for very deep CNNs with many layers and millions of parameters, making it difficult for usage in resource-limited hardware. The study found that vector quantization methods offer a clear gain over existing matrix factorization methods for compressing storage demanding dense connected layers while maintaining model size and recognition accuracy. The study achieved 16-24 times compression of the network for the 1000-category classification task in the ImageNet challenge with only a 1% loss of classification accuracy.


## Target Task

computer vision

## Content

<Abstract: >Deep convolutional neural networks (CNN) has become the most promising
method for object recognition, repeatedly demonstrating record breaking results
for image classiﬁcation and object detection in recent years. However, a very
deep CNN generally involves many layers with millions of parameters, making
the storage of the network model to be extremely large. This prohibits the
usage of deep CNNs on resource limited hardware, especially cell phones or
other embedded devices. In this paper, we tackle this model storage issue by
investigating information theoretical vector quantization methods for compressing
the parameters of CNNs. In particular, we have found in terms of compressing
the most storage demanding dense connected layers, vector quantization methods
have a clear gain over existing matrix factorization methods. Simply applying
k-means clustering to the weights or conducting product quantization can lead
to a very good balance between model size and recognition accuracy. For
the 1000-category classiﬁcation task in the ImageNet challenge, we are able
to achieve 16-24 times compression of the network with only 1% loss of
classiﬁcation accuracy using the state-of-the-art CNN.



---

