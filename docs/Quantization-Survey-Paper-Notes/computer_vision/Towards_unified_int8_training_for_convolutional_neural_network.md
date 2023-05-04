# Towards unified int8 training for convolutional neural network

## Summary

Summary: This paper presents a unified 8-bit training framework for common CNNs that ensures stable training and high accuracy. The authors identified four distinctive characteristics of gradients and used them to guide gradient quantization. They also derived two principles for stable INT8 training and proposed two universal techniques to avoid illegal gradient update and reduce direction deviation. The framework promises accurate and efficient INT8 training for various networks and tasks, including object detection. Additionally, it reduces training time by 22% on a Pascal GPU without complex optimization effort.


## Target Task

computer vision

## Content

<Abstract:>
Recently, there has been extensive research on low-bit network quantization to accelerate the inference of convolutional neural networks (CNNs). However, low-bit training with quantized gradients for accelerating the backward process often leads to unstable training and even crashes. Therefore, a unified low-bit training framework that can support diverse networks on various tasks is lacking. In this paper, we present a  unified 8-bit (INT8) training framework for common CNNs that ensures stable training and high accuracy. We empirically identify the four distinctive characteristics of gradients and use them to guide gradient quantization. Moreover, we provide an in-depth analysis of the convergence bound and derive two principles for stable INT8 training. We also propose two universal techniques, Direction Sensitive Gradient Clipping and Deviation Counteractive Learning Rate Scaling, to further avoid illegal gradient update and reduce direction deviation. The experiments show that our framework promises accurate and efficient INT8 training for various networks and tasks, including object detection, which prior studies have not succeeded in. Additionally, our framework is flexible and reduces training time by 22% on a Pascal GPU without complex optimization effort.



---

