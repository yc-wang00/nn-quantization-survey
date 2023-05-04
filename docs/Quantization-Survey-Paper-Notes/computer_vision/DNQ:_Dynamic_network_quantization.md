# DNQ: Dynamic network quantization

## Summary

Summary: The paper proposes a Dynamic Network Quantization (DNQ) framework for network quantization, which includes a bit-width controller and a quantizer. This approach uses policy gradient to train the bit-width controller to learn the bit-width of each layer of the network, allowing for a trade-off between accuracy and compression ratio. The quantizer uses quantization distance as the criterion for weights importance during quantization. Results demonstrate the effectiveness of the proposed approach.


## Target Task

computer vision

## Content

<Abstract:>
Network quantization is an effective method for the deployment of neural networks on memory and energy constrained mobile devices. In this paper, we propose a Dynamic Network Quantization (DNQ) framework which is composed of two modules: a bit-width controller and a quantizer. Unlike most existing quantization methods that use a universal quantization bit-width for the whole network, we utilize policy gradient to train an agent to learn the bit-width of each layer by the bit-width controller. This controller can make a trade-off between accuracy and compression ratio. Given the quantization bit-width sequence, the quantizer adopts the quantization distance as the criterion of the weights importance during quantization. We extensively validate the proposed approach on various main-stream neural networks and obtain impressive results.



---

