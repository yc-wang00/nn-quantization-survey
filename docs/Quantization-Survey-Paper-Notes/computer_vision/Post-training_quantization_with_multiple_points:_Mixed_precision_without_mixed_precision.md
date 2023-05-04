# Post-training quantization with multiple points: Mixed precision without mixed precision

## Summary

Summary: The paper proposes a multipoint quantization method for the post-training quantization problem of discretizing the weights of pre-trained deep neural networks without re-training the model. They construct the multipoint quantization with an efficient greedy selection procedure and adaptively decide the number of low precision points on each quantized weight vector based on the error of its output. The method can be implemented by common operands with almost no memory and computation overhead. The proposed method outperforms a range of state-of-the-art methods on ImageNet classification, and it can be generalized to more challenging tasks like PASCAL VOC object detection.


## Target Task

computer vision

## Content

<Abstract: >
We consider the post-training quantization problem, which discretizes the weights of pre-trained deep neural networks without re-training the model. We propose multipoint quantization, a quantization method that approximates a full-precision weight vector using a linear combination of multiple vectors of low-bit numbers. Computationally, we construct the multipoint quantization with an efficient greedy selection procedure and adaptively decide the number of low precision points on each quantized weight vector based on the error of its output. Empirically, our method can be implemented by common operands, bringing almost no memory and computation overhead. We show that our method outperforms a range of state-of-the-art methods on ImageNet classification and it can be generalized to more challenging tasks like PASCAL VOC object detection.



---

