# Pqk: Model compression via pruning, quantization, and knowledge distillation

## Summary

<Summary: > The paper proposes a model compression technique called PQK that uses pruning, quantization, and knowledge distillation to create power-efficient and lightweight deep neural networks for edge devices. PQK has two phases, in phase one iterative pruning and quantization-aware training are used to create a lightweight model. In phase two, a teacher network is created by adding unimportant weights to a pruned network, which is used to train the pruned network as a student network. The effectiveness of PQK is verified on keyword spotting and image recognition.


## Target Task

computer vision

## Content

<Abstract: > 
We propose a model compression method called PQK, which stands for pruning, quantization, and knowledge distillation, to make Deep Neural Networks (DNNs) power efficient and lightweight for edge devices with limited computational resources. Unlike traditional pruning and knowledge distillation, PQK makes use of unimportant weights pruned in the pruning process to make a teacher network for training a better student network without pre-training the teacher model. PQK has two phases. Phase 1 exploits iterative pruning and quantization-aware training to make a lightweight and power-efficient model. In phase 2, we make a teacher network by adding unimportant weights unused in phase 1 to a pruned network. By using this teacher network, we train the pruned network as a student network. We apply our method to the recognition model and verify the effectiveness of PQK on keyword spotting (KWS) and image recognition.



---

