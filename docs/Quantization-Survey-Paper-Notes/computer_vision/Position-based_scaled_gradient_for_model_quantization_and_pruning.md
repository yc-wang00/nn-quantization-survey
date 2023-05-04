# Position-based scaled gradient for model quantization and pruning

## Summary

Summary: The article proposes PSG (position-based scaled gradient) that scales the gradient based on the weight vector position, which acts as a regularizer to the weight vectors that is favorable for model compression domains such as quantization and pruning. PSG reduces the gap between the weight distributions of a full-precision model and its compressed counterpart, resulting in the versatile deployment of a model either as an uncompressed mode or as a compressed mode. The proposed PSG is effective in both domains of pruning and quantization even for extremely low bits, as demonstrated in experimental results on CIFAR-10/100 and ImageNet datasets. The code for PSG is released in Github.


## Target Task

computer vision

## Content

<Abstract: >
We propose the position-based scaled gradient (PSG) that scales the gradient depending on the position of a weight vector to make it more compression-friendly. First, we theoretically show that applying PSG to the standard gradient descent (GD), which is called PSGD, is equivalent to the GD in the warped weight space, a space made by warping the original weight space via an appropriately designed invertible function. Second, we empirically show that PSG acting as a regularizer to the weight vectors is favorable for model compression domains such as quantization and pruning. PSG reduces the gap between the weight distributions of a full-precision model and its compressed counterpart. This enables the versatile deployment of a model either as an uncompressed mode or as a compressed mode depending on the availability of resources. The experimental results on CIFAR-10/100 and ImageNet datasets show the effectiveness of the proposed PSG in both domains of pruning and quantization even for extremely low bits. The code is released in Github2.



---

