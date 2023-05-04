# Forward and backward information retention for accurate binary neural networks

## Summary

<Summary: > The paper proposes an approach called Information Retention Network (IR-Net) to address the information loss in both forward and backward propagation during neural network quantization. The approach mainly relies on two technical contributions, Libra Parameter Binarization (Libra-PB) and Error Decay Estimator (EDE), for balanced weights in forward propagation and approximating the sign function in backward propagation, respectively. Empirical results show that IR-Net consistently outperforms state-of-the-art quantization methods on CIFAR-10 and ImageNet datasets.


## Target Task

computer vision

## Content

<Abstract: >Weight and activation binarization is an effective approach to deep neural network compression and can accelerate the inference by leveraging bitwise operations. Although many binarization methods have improved the accuracy of the model by minimizing the quantization error in forward propagation, there remains a noticeable performance gap between the binarized model and the full-precision one. Our empirical study indicates that the quantization brings information loss in both forward and backward propagation, which is the bottleneck of training accurate binary neural networks. To address these issues, we propose an Information Retention Network (IR-Net) to retain the information that consists in the forward activations and backward gradients. IR-Net mainly relies on two technical contributions: (1) Libra Parameter Binarization (Libra-PB): simultaneously minimizing both quantization error and information loss of parameters by balanced and standardized weights in forward propagation; (2) Error Decay Estimator (EDE): minimizing the information loss of gradients by gradually approximating the sign function in backward propagation, jointly considering the updating ability and accurate gradients. We are the first to investigate both forward and backward processes of binary networks from the unified information perspective, which provides new insight into the mechanism of network binarization. Comprehensive experiments with various network structures on CIFAR-10 and ImageNet datasets manifest that the proposed IR-Net can consistently outperform state-of-the-art quantization methods.



---

