# Hawq-v2: Hessian aware trace-weighted quantization of neural networks

## Summary

Summary: HAWQ-V2 is a mixed-precision quantization method that automatically selects bit precisions without manual intervention. It uses a Pareto frontier based method and the average Hessian trace as the sensitivity metric. This Hessian based analysis for mixed-precision activation quantization produces the best object detection results and achieved state-of-the-art quantization results for InceptionV3, ResNet50, and SqueezeNext.


## Target Task

computer vision

## Content

<Abstract: >Quantization is a method to reduce the memory footprint and inference time of Neural Networks. However, low precision quantization can lead to significant model accuracy degradation. Mixed-precision quantization keeps more sensitive layers at higher precision, but the search space for this method is exponential in the number of layers. Hessian-based frameworks have been proposed to reduce the search space, but they have limitations. We present HAWQ-V2, which theoretically shows that the average Hessian trace is the right sensitivity metric and uses a Pareto frontier based method for automatic bit precision selection without manual intervention. HAWQ-V2 develops the first Hessian based analysis for mixed-precision activation quantization, which produces the best object detection results. State-of-the-art quantization results have been achieved for InceptionV3, ResNet50, and SqueezeNext, all without manual bit selection. Object detection results have outperformed direct uniform quantization and the recently proposed method of FQN.



---

