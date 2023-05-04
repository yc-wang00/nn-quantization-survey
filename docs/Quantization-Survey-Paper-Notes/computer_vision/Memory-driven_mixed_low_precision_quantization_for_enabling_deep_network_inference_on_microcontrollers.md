# Memory-driven mixed low precision quantization for enabling deep network inference on microcontrollers

## Summary

<Summary: > The paper presents a new method for deploying high-accuracy deep networks on microcontrollers with memory and computational limitations using mixed low-bitwidth compression and integer-only operations. The method cuts the number of bits of most memory-demanding layers and determines the minimum bit precision of every activation and weight tensor given the memory constraints of a device. The approach was applied on STM32H7 microcontroller with only 2MB flash memory and 512KB RAM and reported an improvement in top1 accuracy by 8% compared to previously published 8 bit implementations.


## Target Task

computer vision

## Content

<Abstract: >This paper presents a novel methodology for deploying high-accuracy deep networks on microcontrollers with memory and computational limitations. The approach uses mixed low-bitwidth compression and integer-only operations for the inference graph. The method cuts the number of bits of the most memory-demanding layers to determine the minimum bit precision of every activation and weight tensor given the memory constraints of a device. The paper reports the latency-accuracy evaluation of mixed-precision MobilenetV1 family networks on a STM32H7 microcontroller with only 2MB of FLASH memory and 512kB of RAM. The results demonstrate an end-to-end deployment of an integer-only Mobilenet network with Top1 accuracy of 68%, which improves by 8% the Top1 accuracy with respect to previously published 8 bit implementations for microcontrollers.



---

