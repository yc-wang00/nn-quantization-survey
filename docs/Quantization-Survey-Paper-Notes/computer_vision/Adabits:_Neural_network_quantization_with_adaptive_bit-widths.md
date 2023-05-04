# Adabits: Neural network quantization with adaptive bit-widths

## Summary

<Summary: > The paper proposes a new concept of adaptive bit-widths of weights and activations in deep neural networks for flexible and efficient deployment on different platforms. They experiment with different approaches and discover that joint training produces comparable performance on the adaptive model as individual models. They also propose a new technique named Switchable Clipping Level (S-CL) to further improve quantized models at the lowest bit-width. The proposed techniques can offer a distinct opportunity for improved accuracy-efficiency trade-off as well as instant adaptation according to the platform constraints in real-world applications.


## Target Task

computer vision

## Content

<Abstract: > 
In this paper, the authors propose a new concept, adaptive bit-widths of weights and activations in deep neural networks, to achieve flexible and efficient deployment on different platforms with resource budgets. They experiment with several approaches, including direct adaptation, progressive training, and joint training, and discover that joint training produces comparable performance on the adaptive model as individual models. They also propose a new technique named Switchable Clipping Level (S-CL) to further improve quantized models at the lowest bit-width. They apply these techniques to several models and demonstrate that bit-width of weights and activations is a new option for adaptively executable deep neural networks, offering a distinct opportunity for improved accuracy-efficiency trade-off as well as instant adaptation according to the platform constraints in real-world applications.



---

