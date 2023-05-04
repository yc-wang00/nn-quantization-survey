# Low-bit quantization needs good distribution

## Summary

Summary: The paper proposes a low-bit quantization technique called the Scale-Clip technique which can reshape weights or activations dynamically. The Group-based Quantization algorithm is proposed to split filters into several groups, increasing performance for a low-bit model. The proposed Group-based Distribution Reshaping Quantization (GDRQ) framework, which integrates Scale-Clip with Group-based Quantization, achieves better performance than state-of-the-art quantization methods on various networks and vision tasks. The ResNet-50 model with 2-bit weights and 4-bit activations achieved less than 1% accuracy drop on ImageNet classification task, which is a new state-of-the-art.


## Target Task

computer vision

## Content

<Abstract:>
Low-bit quantization is a challenge in maintaining high performance with limited model capacity. We propose the Scale-Clip technique, which can reshape weights or activations into a uniform-like distribution dynamically. To increase the model capability for a low-bit model, we propose the Group-based Quantization algorithm to split filters into several groups. Finally, we integrate Scale-Clip technique with Group-based Quantization algorithm and propose the Group-based Distribution Reshaping Quantization (GDRQ) framework. The experiments on various networks and vision tasks demonstrate that our framework achieves better performance than state-of-the-art quantization methods. The ResNet-50 model with 2-bit weights and 4-bit activations obtained by our framework achieves less than 1% accuracy drop on ImageNet classification task, which is a new state-of-the-art.



---

