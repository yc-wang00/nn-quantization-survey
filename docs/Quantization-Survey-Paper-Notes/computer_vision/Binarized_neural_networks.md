# Binarized neural networks

## Summary

Summary: The paper introduces a method to train Binarized Neural Networks that achieved nearly state-of-the-art results over MNIST, CIFAR-10, and SVHN datasets. BNNs drastically reduce memory size and replace most arithmetic operations with bit-wise operations which is expected to substantially improve power-efficiency. The code for training and running BNNs is also available online.


## Target Task

computer vision

## Content

<Abstract: >We introduce a method to train Binarized Neural Networks (BNNs) - neural networks with binary weights and activations at run-time. To validate the effectiveness of BNNs, we conducted two sets of experiments on the Torch7 and Theano frameworks. On both, BNNs achieved nearly state-of-the-art results over the MNIST, CIFAR-10 and SVHN datasets. We also report our preliminary results on the challenging ImageNet dataset. During the forward pass, BNNs drastically reduce memory size and accesses, and replace most arithmetic operations with bit-wise operations, which is expected to substantially improve power-efﬁciency. The code for training and running our BNNs is available online.



---

