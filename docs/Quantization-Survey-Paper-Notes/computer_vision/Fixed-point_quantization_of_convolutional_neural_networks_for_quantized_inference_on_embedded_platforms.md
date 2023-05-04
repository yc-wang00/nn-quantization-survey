# Fixed-point quantization of convolutional neural networks for quantized inference on embedded platforms

## Summary

Summary: The paper proposes a method to optimize the quantization of weights, biases, and activations of each layer of a pretrained CNN to allow for deployment on embedded platforms. The method optimizes low bitwidth fixed-point representations for each parameter while controlling the loss in inference accuracy, resulting in a low precision CNN with accuracy losses of less than 1%. The paper finds that layer-wise quantization of parameters significantly helps in the process of quantization.


## Target Task

computer vision

## Content

<Abstract:>
Convolutional Neural Networks (CNNs) are known to be an effective method for image classification tasks but their high computational complexity and memory usage make them impractical for deployment on embedded platforms. To address this issue, we propose a method to optimize the quantization of weights, biases, and activations of each layer of a pretrained CNN without retraining it. Our method optimizes low bitwidth fixed-point representations for each parameter while controlling the loss in inference accuracy, resulting in a low precision CNN with accuracy losses of less than 1%. Compared to a method used by commercial tools that quantize parameters to 8-bits, our approach offers lower memory consumption and cost of executing multiplications. We find that layer-wise quantization of parameters significantly helps in the process of quantization.



---

