# DPOQ: dynamic precision onion quantization

## Summary

<Summary: > The paper proposes a new strategy called Dynamic Precision Onion Quantization (DPOQ) that enables dynamic precision in neural network parameters. The authors train the network using scaled gradients loss and propose Precision Shift Batch Normalization (PSBN) to improve performance and make different precision networks compatible. They also propose an adaptable input-specific inference mechanism based on this architecture. Experiments on CIFAR and ImageNet dataset show DPOQ achieves higher accuracy and better flexibility than individual quantization.


## Target Task

computer vision

## Content

<Abstract: >In this paper, we propose a novel network architecture reuse strategy enabling dynamic precision in parameters, named dynamic precision onion quantization (DPOQ). We train the network using the joint loss with scaled gradients and propose the precision shift batch normalization (PSBN) to further improve performance and make different precision networks compatible with each other. We also propose a scalable input-specific inference mechanism based on this architecture to make the network more adaptable. Experiments on the CIFAR and ImageNet dataset have shown that our DPOQ achieves higher accuracy and better flexibility than individual quantization.



---

