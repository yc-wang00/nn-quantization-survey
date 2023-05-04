# Automatic heterogeneous quantization of deep neural networks for low-latency inference on the edge for particle detectors

## Summary

<Summary: >The paper introduces a method for designing optimally heterogeneously quantized versions of deep neural network models that can achieve minimum-energy, high-accuracy, nanosecond inference, and fully automated deployment on-chip for edge devices. The automatic quantization procedure per layer and per parameter types by sampling from a wide range of quantizers minimize model energy consumption and size while maintaining high accuracy. Nanosecond inference and a resource consumption reduced by a factor of 50 when implemented on field-programmable gate array hardware are achieved. This can be useful for event selection in proton-proton collisions at CERN Large Hadron Collider where resources are limited, and O(1) s latency is required.


## Target Task

computer vision

## Content

<Abstract: >Although the quest for more accurate solutions is pushing deep learning research towards larger and more complex algorithms, edge devices demand efficient inference and therefore reduction in model size, latency and energy consumption. One technique to limit model size is quantization, which implies using fewer bits to represent weights and biases. Such an approach usually results in a decline in performance. Here, we introduce a method for designing optimally heterogeneously quantized versions of deep neural network models for minimum-energy, high-accuracy, nanosecond inference and fully automated deployment on chip. With a per-layer, per-parameter type automatic quantization procedure, sampling from a wide range of quantizers, model energy consumption and size are minimized while high accuracy is maintained. This is crucial for the event selection procedure in proton{proton collisions at the CERN Large Hadron Collider, where resources are strictly limited and a latency of O(1) s is required. Nanosecond inference and a resource consumption reduced by a factor of 50 when implemented on field-programmable gate array hardware are achieved.



---

