# Verifying Quantized Neural Networks using SMT-Based Model Checking

## Summary

<Summary: > The paper discusses the development and evaluation of a symbolic verification framework for Artificial Neural Networks (ANNs) through software model checking and satisfiability modulo theories to address concerns relating to their reliability, black-box nature, and sensitivity to quantization errors when deployed in safety-critical systems. The verification approach was found to analyze larger ANN implementations and reduce the verification time compared to state-of-the-art techniques, also providing formal guarantees on their safe behavior.


## Target Task

computer vision

## Content

<Abstract: >Artificial Neural Networks (ANNs) are being deployed for an increasing number of safety-critical applications, including autonomous cars and medical diagnosis. However, concerns about their reliability have been raised due to their black-box nature and apparent fragility to adversarial attacks. These concerns are amplified when ANNs are deployed on restricted system, which limit the precision of mathematical operations and thus introduce additional quantization errors. Here, we develop and evaluate a novel symbolic verification framework using software model checking (SMC) and satisfiability modulo theories (SMT) to check for vulnerabilities in ANNs. More specifically, we propose several ANN-related optimizations for SMC, including invariant inference via interval analysis, slicing, expression simplifications, and discretization of non-linear activation functions. With this verification framework, we can provide formal guarantees on the safe behavior of ANNs implemented both in floating- and fixed-point arithmetic. In this regard, our verification approach was able to verify and produce adversarial examples for 52test cases spanning image classification and general machine learning applications. Furthermore, for small- to medium-sized ANN, our approach completes most of its verification runs in minutes. Moreover, in contrast to most state-of-the-art methods, our approach is not restricted to specific choices regarding activation functions and non-quantized representations. Our experiments show that our approach can analyze larger ANN implementations and substantially reduce the verification time compared to state-of-the-art techniques that use SMT solving.



---

