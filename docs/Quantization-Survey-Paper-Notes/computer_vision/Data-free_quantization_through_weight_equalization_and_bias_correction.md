# Data-free quantization through weight equalization and bias correction

## Summary

Summary: The paper introduces a data-free quantization technique for deep neural networks that does not require fine-tuning or hyperparameter selection. It achieves high performance on common computer vision architectures and tasks through weight equalization and bias correction. State-of-the-art quantized model performance is achieved on architectures like MobileNet, and the method extends to other computer vision architectures and tasks like semantic segmentation and object detection.


## Target Task

computer vision

## Content

<Abstract:>
We introduce a data-free quantization method for deep neural networks that does not require fine-tuning or hyperparameter selection. It achieves near-original model performance on common computer vision architectures and tasks. Our approach relies on equalizing the weight ranges in the network by making use of a scale-equivariance property of activation functions. In addition, the method corrects biases in the error that are introduced during quantization. This improves quantization accuracy performance and can be applied to many common computer vision architectures with a straightforward API call. We achieve state-of-the-art quantized model performance for common architectures, such as the MobileNet family, and show that the method also extends to other computer vision architectures and tasks such as semantic segmentation and object detection.



---

