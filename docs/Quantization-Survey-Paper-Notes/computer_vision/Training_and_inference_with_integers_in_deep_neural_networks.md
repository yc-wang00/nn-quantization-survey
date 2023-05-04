# Training and inference with integers in deep neural networks

## Summary

<Summary: > The paper proposes WAGE, a novel method to discretize both training and inference processes in deep neural networks, with low-bitwidth integers. The method includes linearly constraining weights, activations, gradients, and errors among layers, replacing batch normalization by a constant scaling layer, and simplifying other components for integer implementation in pure discrete data flow for fixed-point devices. The authors demonstrate improved accuracies on multiple datasets and potential deployment of training in hardware systems, such as integer-based deep learning accelerators and neuromorphic chips, with comparable accuracy and higher energy efficiency.


## Target Task

computer vision

## Content

<Abstract: >In this work, the authors propose a novel method called WAGE to discretize both training and inference processes in deep neural networks with low-bitwidth integers. The method shifts and linearly constrains weights, activations, gradients and errors among layers. The authors also replace batch normalization by a constant scaling layer, and simplify other components for integer implementation in pure discrete dataflow for fixed-point devices. The authors demonstrate improved accuracies on multiple datasets and potential deployment of training in hardware systems such as integer-based deep learning accelerators and neuromorphic chips with comparable accuracy and higher energy efficiency, which is important for future AI applications.



---

