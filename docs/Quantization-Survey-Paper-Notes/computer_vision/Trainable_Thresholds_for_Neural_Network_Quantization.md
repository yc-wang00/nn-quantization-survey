# Trainable Thresholds for Neural Network Quantization

## Summary

Summary: The paper proposes two methods for optimizing the training with quantization procedure to maintain the accuracy of full-precision neural networks for modern mobile architectures like Mobilenet-v1, MobileNet-v2, and MNAS. By reducing the train dataset size and small number of trainable parameters, the models achieved high accuracy in less time and resources. The proposed techniques are available on Github.


## Target Task

computer vision

## Content

<Abstract:>
The neural network quantization is highly desired procedure to perform before running neural networks on mobile devices. Quantization without fine-tuning leads to accuracy drop of the model, whereas commonly used training with quantization is done on the full set of the labeled data and therefore is both time- and resource-consuming. Real-life applications require simplification and acceleration of quantization procedure that will maintain the accuracy of full-precision neural network, especially for modern mobile neural network architectures like Mobilenet-v1, MobileNet-v2 and MNAS. Here we present two methods to significantly optimize the training with quantization procedure. The first one is introducing the trained scale factors for the discretization thresholds that are separate for each filter. The second one is based on mutual rescaling of consequent depth-wise separable convolution and convolution layers. Using the proposed techniques, we quantize the modern mobile architectures of neural networks with the set of train data of only 10% of the total ImageNet 2012 sample. Such reduction of train dataset size and small number of trainable parameters allow fine-tuning the network for several hours while maintaining the high accuracy of quantized model (accuracy drop was less than 0.5%). Ready-for-use models and code are available at: https://github.com/agoncharenko1992/FAT-fast-adjustable-threshold. Keywords: Distillation, Machine Learning, Neural Networks, Quantization.



---

