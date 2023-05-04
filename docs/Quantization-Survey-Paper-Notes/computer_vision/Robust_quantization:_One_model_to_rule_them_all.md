# Robust quantization: One model to rule them all

## Summary

<Summary: The paper proposes a method for robust quantization of neural networks that enables a single generic model to operate at various bit-widths and quantization policies, providing intrinsic robustness to the models against a broad range of quantization processes. The method is validated on different ImageNet models.>


## Target Task

computer vision

## Content

<Abstract:>
Neural network quantization methods often involve simulating the quantization process during training, making the trained model highly dependent on the target bit-width and precise way quantization is performed. Robust quantization offers an alternative approach with improved tolerance to different classes of data-types and quantization policies. It opens up new exciting applications where the quantization process is not static and can vary to meet different circumstances and implementations. To address this issue, we propose a method that provides intrinsic robustness to the model against a broad range of quantization processes. Our method is motivated by theoretical arguments and enables us to store a single generic model capable of operating at various bit-widths and quantization policies. We validate our method’s effectiveness on different ImageNet models.



---

