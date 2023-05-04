# CoCo-FL: Communication-and Computation-Aware Federated Learning via Partial NN Freezing and Quantization

## Summary

<Summary: >The paper presents a Federated Learning technique called CoCoFL, that maintains the full NN structure on all devices and adapts to heterogeneous resources by freezing and quantizing selected layers, enhancing the accuracy of FL systems and providing fairness to constrained devices. CoCoFL outperforms existing techniques and can reach up to 8.9p.p. higher accuracy with independent and up to 20p.p. with non-independent, non-identical distributed data.


## Target Task

computer vision

## Content

<Abstract: >Devices participating in federated learning (FL) usually have diverse resources, such as computation, communication, and memory, and in synchronous FL, all devices need to finish training by the same deadline set by the server. Existing techniques that train subsets of the neural network (NN) model on less capable devices, i.e., reducing neurons/filters, is inefficient and does not provide fairness to constrained devices, especially in cases when there is a skewed distribution of class labels across devices. In this paper, a novel Federated Learning technique, called CoCoFL, is proposed that maintains the full NN structure on all devices, adapting to heterogeneous resources by freezing and quantizing selected layers, allowing devices to reach high accuracy while utilizing available resources, increasing fairness and improving the final accuracy of the model. CoCoFL is evaluated, demonstrating that it outperforms existing techniques, reaching up to 8.9p.p. higher accuracy with independent and up to 20p.p. with non-independent, non-identical distributed data, enhancing the accuracy of FL systems.



---

