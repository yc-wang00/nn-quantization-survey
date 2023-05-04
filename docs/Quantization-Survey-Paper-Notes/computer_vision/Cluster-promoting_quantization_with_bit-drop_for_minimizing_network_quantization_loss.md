# Cluster-promoting quantization with bit-drop for minimizing network quantization loss

## Summary

Summary: The paper proposes a novel quantization method, Cluster-Promoting Quantization (CPQ), to reduce the bit-length of neural network weights and activations for resource-limited devices. CPQ finds optimal quantization grids which encourage full-precision weights to gather around those quantization grids cohesively during training, reducing the quantization errors that typically result from network quantization.


## Target Task

computer vision

## Content

<Abstract: Network quantization, which aims to reduce the bit-lengths of the network weights and activations, has emerged for their deployments to resource-limited devices. Although recent studies have successfully discretized a full-precision network, they still incur large quantization errors after training, thus giving rise to a significant performance gap between a full-precision network and its quantized counterpart. In this work, we propose a novel quantization method for neural networks, Cluster-Promoting Quantization (CPQ) that finds the optimal quantization grids while naturally encouraging the underlying full-precision weights to gather around those quantization grids cohesively during training.>



---

