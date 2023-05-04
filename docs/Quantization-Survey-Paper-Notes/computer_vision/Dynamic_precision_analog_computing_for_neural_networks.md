# Dynamic precision analog computing for neural networks

## Summary

Summary: The paper proposes extending analog computing architectures to support varying levels of precision to decrease the impact of noise, and a method for learning the precision of each layer of a pre-trained model without retraining network weights. The authors evaluate this method on analog architectures subject to various noise sources and find that employing dynamic precision reduces energy consumption significantly for computer vision and natural language processing models with <2% accuracy degradation. They apply dynamic precision to a shot-noise limited homodyne optical neural network and simulate inference at an optical energy consumption of 2.7 aJ/MAC for Resnet50 and 1.6 aJ/MAC for BERT.


## Target Task

computer vision

## Content

Abstract: Analog electronic and optical computing have been recognized as a promising approach for accelerating matrix multiplications, a computationally expensive operation in deep learning. However, analog computing exhibits tremendous advantages over digital computing only when operations are executed at low precision. In this work, the authors propose extending analog computing architectures to support varying levels of precision by repeating operations and averaging the result, decreasing the impact of noise. They also propose a method for learning the precision of each layer of a pre-trained model without retraining network weights. The authors evaluate this method on analog architectures subject to a variety of noise sources such as shot noise, thermal noise, and weight noise and find that employing dynamic precision reduces energy consumption by up to 89% for computer vision models such as Resnet50 and by 24% for natural language processing models such as BERT. In one example, they apply dynamic precision to a shot-noise limited homodyne optical neural network and simulate inference at an optical energy consumption of 2.7 aJ/MAC for Resnet50 and 1.6 aJ/MAC for BERT with <2% accuracy degradation.



---

