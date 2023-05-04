# Rotated binary neural network

## Summary

<Summary: >This paper provides a solution to the major impediment that the Binary Neural Network (BNN) faces when reducing deep neural network complexity, which is severe performance degradation due to the large quantization error between the full-precision weight vector and its binary vector. The authors introduce the Rotated Binary Neural Network (RBNN), which considers the angle alignment between the full-precision weight vector and its binarized version. The RBNN uses rotating techniques at the beginning of each training epoch to reduce the angular bias, leading to about a 50% weight flip maximizing information gain. Additionally, the paper proposes a training-aware approximation of the sign function for the gradient backward.  Experiments on CIFAR-10 and ImageNet demonstrate that RBNN performs better than many state-of-the-art methods.


## Target Task

computer vision

## Content

<Abstract: >Binary Neural Network (BNN) shows its predominance in reducing the complexity
of deep neural networks. However, it suffers severe performance degradation. One
of the major impediments is the large quantization error between the full-precision
weight vector and its binary vector. Previous works focus on compensating for
the norm gap while leaving the angular bias hardly touched. In this paper, for
the ﬁrst time, we explore the inﬂuence of angular bias on the quantization error
and then introduce a Rotated Binary Neural Network (RBNN), which considers
the angle alignment between the full-precision weight vector and its binarized
version. At the beginning of each training epoch, we propose to rotate the full-
precision weight vector to its binary vector to reduce the angular bias. To avoid
the high complexity of learning a large rotation matrix, we further introduce a
bi-rotation formulation that learns two smaller rotation matrices. In the training
stage, we devise an adjustable rotated weight vector for binarization to escape the
potential local optimum. Our rotation leads to around 50% weight ﬂips which
maximize the information gain. Finally, we propose a training-aware approximation
of the sign function for the gradient backward. Experiments on CIFAR-10 and
ImageNet demonstrate the superiorities of RBNN over many state-of-the-arts. Our
source code, experimental settings, training logs and binary models are available at
https://github.com/lmbxmu/RBNN.



---

