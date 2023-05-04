# Trained ternary quantization

## Summary

Summary: The paper proposes Trained Ternary Quantization (TTQ) to reduce the precision of weights in neural networks to ternary values for easy deployment on mobile devices with limited power budgets. The method has little accuracy degradation and can even improve the accuracy of some models, and the models are 16 times smaller than full-precision models. Experiments show that the TTQ outperforms previous ternary models and even full-precision models in some cases.


## Target Task

computer vision

## Content

<Abstract: >Deep neural networks are widely used in machine learning applications. However, the deployment of large neural networks models can be difﬁcult to deploy on mobile devices with limited power budgets. To solve this problem, we propose Trained Ternary Quantization (TTQ), a method that can reduce the precision of weights in neural networks to ternary values. This method has very little accuracy degradation and can even improve the accuracy of some models (32, 44, 56-layer ResNet) on CIFAR-10 and AlexNet on ImageNet. And our AlexNet model is trained from scratch, which means it’s as easy as to train normal full precision model. We highlight our trained quantization method that can learn both ternary values and ternary assignment. During inference, only ternary values (2-bit weights) and scaling factors are needed, therefore our models are nearly 16smaller than full-precision models. Our ternary models can also be viewed as sparse binary weight networks, which can potentially be accelerated with custom circuit. Experiments on CIFAR-10 show that the ternary models obtained by trained quantization method outperform full-precision models of ResNet-32,44,56 by 0.04%, 0.16%, 0.36%, respectively. On ImageNet, our model outperforms full-precision AlexNet model by 0.3% of Top-1 accuracy and outperforms previous ternary models by 3%.



---

