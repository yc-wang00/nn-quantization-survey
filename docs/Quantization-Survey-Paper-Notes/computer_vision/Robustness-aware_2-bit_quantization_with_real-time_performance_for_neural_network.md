# Robustness-aware 2-bit quantization with real-time performance for neural network

## Summary

Summary: The paper proposes a new 2-bit quantization scheme for neural networks based on binary neural networks and generative adversarial network (GANs) to improve performance and consider the robustness of the quantized neural network. The proposed method uses shift addition operation instead of multiply-accumulate to speed up the network and a structural loss to preserve structural information after quantization. Furthermore, the method introduces a non-sensitive perturbation loss function to consider the robustness of the quantized neural network. Experimental results demonstrate that the proposed scheme is competitive and robust under adversarial attacks.


## Target Task

computer vision

## Content

<Abstract: >Quantized neural network with a reduced bit precision is an effective solution to reduce the computational and memory resource requirements and plays a vital role in machine learning. However, it is still challenging to avoid the significant accuracy degradation due to its numerical approximation and lower redundancy. In this paper, a novel robustness-aware 2-bit quantization scheme is proposed for NN based on binary NN and generative adversarial network (GAN), which improves the performance by enriching the information of binary NN, efficiently extract the structural information and considering the robustness of the quantized NN. Specifically, using shift addition operation to replace the multiply-accumulate in the quantization process which can effectively speed the NN. Meanwhile, a structural loss between the original NN and quantized NN is proposed to such that the structural information of data is preserved after quantization. The structural information learned from NN not only plays an important role in improving the performance but also allows for further finetuning of the quantization network by applying the Lipschitz constraint to the structural loss. In addition, we also for the first time take the robustness of the quantized NN into consideration and propose a non-sensitive perturbation loss function by introducing an extra-neous term of spectral norm. The experiments are conducted on CIFAR-10 and ImageNet datasets with popular NN (such as MoblieNetV2, SqueezeNet, ResNet20, etc.). The experimental results show that the proposed algorithm is more competitive under 2-bit-precision than the state-of-the-art quantization methods. Meanwhile, the experimental results also demonstrate that the proposed method is robust under the FGSM adversarial samples attack.



---

