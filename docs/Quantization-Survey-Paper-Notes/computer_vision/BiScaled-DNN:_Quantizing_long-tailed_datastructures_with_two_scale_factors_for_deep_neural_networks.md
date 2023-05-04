# BiScaled-DNN: Quantizing long-tailed datastructures with two scale factors for deep neural networks

## Summary

<Summary: > 

The paper discusses the use of fixed-point implementations in Deep Neural Networks (DNNs) for energy-constrained platforms. The authors propose a new number representation called BiScaled-FXP, which takes into account that most datastructures in DNNs are long-tailed, with a majority of small values and a small fraction of much larger values. The proposed method is designed to provide better range and resolution for long-tailed datastructures.


## Target Task

computer vision

## Content

<Abstract: >Fixed-point implementations (FxP) are prominently used to realize Deep Neural Networks (DNNs) efficiently on energy-constrained platforms. The choice of bit-width is often constrained by the ability of FxP to represent the entire range of numbers in the datastructure with sufficient resolution. In this work, we leverage a key insight that almost all datastructures in DNNs are long-tailed i.e., a significant majority of the elements are small in magnitude, with a small fraction being orders of magnitude larger. We propose BiScaled-FXP, a new number representation which caters to the disparate range and resolution needs of long-tailed data-structures. </Abstract>



---

