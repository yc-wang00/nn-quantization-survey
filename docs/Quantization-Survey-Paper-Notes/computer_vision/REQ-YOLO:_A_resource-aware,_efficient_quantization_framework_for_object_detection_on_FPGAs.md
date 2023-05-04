# REQ-YOLO: A resource-aware, efficient quantization framework for object detection on FPGAs

## Summary

Summary: REQ-YOLO is a resource-aware, systematic weight quantization framework for object detection that significantly compresses the YOLO model while introducing small accuracy degradation, aiming to achieve real-time and highly-efficient implementations on FPGA. The paper presents detailed hardware implementation of block circulant matrices on CONV layers, an efficient processing element (PE) supporting weight quantization, CONV dataflow and pipelining techniques, design optimization, and a template-based automatic synthesis framework to optimally exploit hardware resource. It also touches upon the requirements of real-time and energy-efficient implementations of DNNs on a power-constrained system and the two research thrusts dedicated to performance and energy efficiency of DNNs.


## Target Task

computer vision

## Content

<Abstract:>
This paper proposes REQ-YOLO, a resource-aware, systematic weight quantization framework for object detection, considering both algorithm and hardware resource aspects in object detection. The proposed framework significantly compresses the YOLO model while introducing very small accuracy degradation. The aim is to achieve real-time and highly-efficient implementations on FPGA, and the paper presents the detailed hardware implementation of block circulant matrices on CONV layers, as well as an efficient processing element (PE) structure supporting the heterogeneous weight quantization, CONV dataflow and pipelining techniques, design optimization, and a template-based automatic synthesis framework to optimally exploit hardware resource. The paper also touches upon the requirements of real-time and energy-efficient implementations of DNNs on a power-constrained system and the two research thrusts dedicated to performance and energy efficiency enhancement of the inference phase of DNNs – model compression techniques and efficient hardware implementations.



---

