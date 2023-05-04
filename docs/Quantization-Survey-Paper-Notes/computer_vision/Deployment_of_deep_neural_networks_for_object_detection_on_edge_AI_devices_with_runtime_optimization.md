# Deployment of deep neural networks for object detection on edge AI devices with runtime optimization

## Summary

Summary: The paper presents a case study on the deployment of object detection networks on an edge AI platform with emphasis on experiences and needs for deployment in embedded environments. The study describes modifications necessary to convert the algorithms from a PyTorch training environment to the deployment environment and evaluates the runtime of the deployed DNN using two different libraries, TensorRT and TorchScript. The study observes slight advantages of TensorRT for convolutional layers and TorchScript for fully connected layers, and concludes that quantization significantly reduces the runtime while having only little impact on the detection performance.


## Target Task

computer vision

## Content

<Abstract: >
Deep neural networks have proven increasingly important for automotive scene understanding with new algorithms offering constant improvements of the detection performance. However, there is little emphasis on experiences and needs for deployment in embedded environments. We therefore perform a case study of the deployment of two representative object detection networks on an edge AI platform. In particular, we consider RetinaNet for image-based 2D object detection and PointPillars for LiDAR-based 3D object detection. We describe the modifications necessary to convert the algorithms from a PyTorch training environment to the deployment environment taking into account the available tools. We evaluate the runtime of the deployed DNN using two different libraries, TensorRT and TorchScript. In our experiments, we observe slight advantages of TensorRT for convolutional layers and TorchScript for fully connected layers. We also study the trade-off between runtime and performance, when selecting an optimized setup for deployment, and observe that quantization significantly reduces the runtime while having only little impact on the detection performance.



---

