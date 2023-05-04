# Ristretto: A framework for empirical study of resource-efficient inference in convolutional neural networks

## Summary

<Summary: >This paper describes Ristretto, a CNN approximation framework that allows for investigating the trade-off between various number representation and word width choices and the classification accuracy of the model. Ristretto analyzes a given CNN with respect to numerical range required to represent weights, activations, and intermediate results of convolutional and fully connected layers, and subsequently simulates the effect of reduced word width or lower precision arithmetic operators on the model accuracy. Additionally, Ristretto can fine-tune a quantized network to enhance its classification accuracy under a given number representation and word width configuration. The aim of the framework is to enable efficient implementation of CNNs on resource-constrained embedded systems.


## Target Task

computer vision

## Content

<Abstract: >Convolutional neural networks (CNN) have led to remarkable progress in key pattern recognition tasks, but inference using pre-trained modern deep CNNs requires significant system resources. To enable efficient implementation on resource-constrained embedded systems, we present Ristretto, a CNN approximation framework that enables empirical investigation of the trade-off between various number representation and word width choices, and the classification accuracy of the model. Ristretto analyzes a given CNN with respect to numerical range required to represent weights, activations and intermediate results of convolutional and fully connected layers, and subsequently, it simulates the impact of reduced word width or lower precision arithmetic operators on the model accuracy. Moreover, Ristretto can fine-tune a quantized network to further improve its classification accuracy under a given number representation and word width configuration.



---

