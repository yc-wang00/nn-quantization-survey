# Shifting capsule networks from the cloud to the deep edge

## Summary

<Summary: >The paper presents an API and a framework to execute quantized Capsule Networks in resource-constrained devices, such as microcontroller units. CapsNets are complex to deploy as they require large memory footprints, thus leading to challenges in adoption at the edge. Results showed a reduction in memory footprint of almost 75%, with accuracy loss ranging from 0.07% to 0.18%. The Arm Cortex-M API enables primary capsule and capsule layers with medium-sized kernels to run in just 119.94 and 90.60 milliseconds, respectively, and for the GAP-8 SoC (RISC-V RV32IMCXpulp @ 170 MHz), latency drops to 7.02 and 38.03 ms, respectively.


## Target Task

computer vision

## Content

<Abstract: > Capsule networks (CapsNets) are an emerging trend in image processing. In contrast to a convolutional neural network, CapsNets are not vulnerable to object deformation, as the relative spatial information of the objects is preserved across the network. However, their complexity is mainly related to the capsule structure and the dynamic routing mechanism, which makes it almost unreasonable to deploy a CapsNet, in its original form, in a resource-constrained device powered by a small microcontroller (MCU). In an era where intelligence is rapidly shifting from the cloud to the edge, this high complexity imposes serious challenges to the adoption of CapsNets at the very edge. To tackle this issue, we present an API for the execution of quantized CapsNets in Arm Cortex-M and RISC-V MCUs. Our software kernels extend the Arm CMSIS-NN and RISC-V PULP-NN to support capsule operations with 8-bit integers as operands. Along with it, we propose a framework to perform post-training quantization of a CapsNet. Results show a reduction in memory footprint of almost 75%, with accuracy loss ranging from 0.07% to 0.18%. In terms of throughput, our Arm Cortex-M API enables the execution of primary capsule and capsule layers with medium-sized kernels in just 119.94 and 90.60 milliseconds (ms), respectively (STM32H755ZIT6U, Cortex-M7 @ 480 MHz). For the GAP-8 SoC (RISC-V RV32IMCXpulp @ 170 MHz), the latency drops to 7.02 and 38.03 ms, respectively. Keywords capsule networks, capsule network quantization, edge, cloud, CMSIS-NN, PULP-NN.



---

