# Bit-flip attack: Crushing neural network with progressive bit search

## Summary

Summary: The paper introduces Bit-Flip Attack (BFA), a novel methodology to maliciously flip a small number of bits within the weight storage memory system of a deep neural network (DNN) and presents an algorithm to identify the most vulnerable bits of DNN weight parameters with a minimum number of bit-flips using Progressive Bit Search (PBS) method. The authors were able to successfully attack a ResNet-18 with only 13 bit-flips and raise concerns about the vulnerability of DNNs to fault injection attacks.


## Target Task

computer vision

## Content

<Abstract: >In this paper, the authors propose a novel methodology to attack the parameters of a deep neural network (DNN) called Bit-Flip Attack (BFA), which maliciously flips a small number of bits within the weight storage memory system. They present an algorithm to identify the most vulnerable bits of DNN weight parameters that can maximize the accuracy degradation with a minimum number of bit-flips. The proposed BFA utilizes a Progressive Bit Search (PBS) method to identify the most vulnerable bit to be flipped. The authors successfully attacked a ResNet-18 with only 13 bit-flips out of 93 million bits, while randomly flipping 100 bits hardly degrades the accuracy by less than 1%. The security challenge of DNN’s parameters is not well explored yet, and fault injection attacks raise concerns about the storage of DNN parameters. The authors highlight that the deployed DNN is vulnerable to popular fault injection techniques such as row hammer and laser beam.



---

