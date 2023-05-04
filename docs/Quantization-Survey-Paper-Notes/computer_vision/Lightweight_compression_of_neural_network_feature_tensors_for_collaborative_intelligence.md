# Lightweight compression of neural network feature tensors for collaborative intelligence

## Summary

Summary: The paper presents a lightweight compression technique designed to compress the activations of a split deep neural network layer without requiring any retraining. The proposed method uses simple and coarse scalar quantization along with clipping, binarization, and entropy coding to compress the activations. The compression technique was evaluated and found to compress 32-bit floating-point activations down to 0.6 to 0.8 bits while keeping the accuracy loss to less than 1%. The proposed compression was compared to the HEVC screen content coding extension and found to consistently provide better inference accuracy, by up to 1.3%. The results suggest that this technique is a promising option for coding a layer's activations in split neural networks for edge/cloud applications.


## Target Task

computer vision

## Content

<Abstract: >
This paper presents a novel lightweight compression technique designed specifically to code the activations of a split deep neural network (DNN) layer for collaborative intelligence applications, without requiring any retraining. The proposed method uses simple and coarse scalar quantization along with clipping, binarization, and entropy coding to compress the activations. The performance of the compression technique was evaluated for popular object-detection and classification DNNs, with the 32-bit floating-point activations compressed down to 0.6 to 0.8 bits, while keeping the loss in accuracy to less than 1%. The proposed compression was compared to the HEVC screen content coding extension and found to consistently provide better inference accuracy, by up to 1.3%. The results suggest that the proposed technique is a promising option for coding a layer's activations in split neural networks for edge/cloud applications.



---

