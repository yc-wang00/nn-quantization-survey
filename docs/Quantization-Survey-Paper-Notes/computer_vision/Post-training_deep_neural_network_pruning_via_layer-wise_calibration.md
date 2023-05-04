# Post-training deep neural network pruning via layer-wise calibration

## Summary

<Summary: >The paper proposes a weight pruning method to compress deep neural networks. The method achieves high accuracy with commodity hardware, such as desktop CPUs or edge devices. A data-free extension is proposed that uses synthetic fractal images to achieve a state-of-the-art result for neural network pruning with a 50% sparsity rate. The method also achieved a 65% sparsity rate for ResNet50 on ImageNet with a 1% top@1 accuracy drop. The code is available as a part of the OpenVINOTM Post-Training Optimization tool.


## Target Task

computer vision

## Content

<Abstract: >We present a post-training weight pruning method for deep neural networks that achieves accuracy levels tolerable for the production setting and that is sufficiently fast to be run on commodity hardware such as desktop CPUs or edge devices. We propose a data-free extension of the approach for computer vision models based on automatically-generated synthetic fractal images. We obtain state-of-the-art results for data-free neural network pruning, with ∼1.5% top@1 accuracy drop for a ResNet50 on ImageNet at 50% sparsity rate. When using real data, we are able to get a ResNet50 model on ImageNet with 65% sparsity rate in 8-bit precision in a post-training setting with a ∼1% top@1 accuracy drop. We release the code as a part of the OpenVINOTM Post-Training Optimization tool1.



---

