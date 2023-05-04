# Non-uniform dnn structured subnets sampling for dynamic inference

## Summary

Summary: The paper proposes a run-time dynamic neural network structure by using a novel DNN sub-network sampling method via non-uniform channel selection for subnets generation. This method allows users to trade off between power, speed, computing load, and accuracy on-the-fly after deployment, depending on the dynamic requirements or specifications of the given system. The proposed model outperforms the same sub-nets trained individually and other related works on CIFAR-10 and ImageNet datasets using ResNets. Furthermore, it achieves latency trade-off among 13.4, 24.6, 41.3, 62.1 (ms) and 30.5, 38.7, 51, 65.4 (ms) for GPU with 128 batch-size and CPU, respectively, on ImageNet using ResNet18.


## Target Task

computer vision

## Content

<Abstract: > With the success of Deep Neural Networks (DNN), many recent works have been focusing on developing hardware-accelerator for power and resource-limited system via model compression techniques, such as quantization, pruning, low-rank approximation and etc. However, almost all existing compressed DNNs are ﬁxed after deployment, which lacks run-time adaptive structure to adapt to its dynamic hardware resource allocation, power budget, throughput requirement, as well as dynamic workload. As the countermeasure, to construct a novel run-time dynamic DNN structure, we propose a novel DNN sub-network sampling method via non-uniform channel selection for subnets generation. Thus, the user can trade off between power, speed, computing load, and accuracy on-the-fly after the deployment, depending on the dynamic requirements or specifications of the given system. We verify the proposed model on both CIFAR-10 and ImageNet dataset using ResNets, which outperforms the same sub-nets trained individually and other related works. It shows that our method can achieve latency trade-off among 13.4, 24.6, 41.3, 62.1(ms) and 30.5, 38.7, 51, 65.4(ms) for GPU with 128 batch-size and CPU, respectively, on ImageNet using ResNet18.



---

