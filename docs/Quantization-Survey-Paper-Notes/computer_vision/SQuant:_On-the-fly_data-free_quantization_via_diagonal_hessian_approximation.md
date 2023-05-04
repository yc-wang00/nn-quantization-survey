# SQuant: On-the-fly data-free quantization via diagonal hessian approximation

## Summary

Summary: The paper introduces SQuant, an on-the-fly data-free quantization framework for deep neural networks (DNN). It employs Constrained Absolute Sum of Error (CASE) to minimize the data-free optimization objective in the discrete domain without the need for any datasets and the awareness of the network architecture. SQuant is an efficient algorithm with no backpropagation, which decreases the computation complexity of the objective solver. It achieves sub-second quantization time and over 30% accuracy improvement compared to existing data-free post-training quantization works, without synthetic datasets or fine-tuning. The framework is open-sourced at https://github.com/clevercool/SQuant.


## Target Task

computer vision

## Content

<Abstract: > Quantization of deep neural networks (DNN) is a suitable technique for compressing and accelerating DNN models. Data-free quantization (DFQ) is preferred when privacy and confidentiality scenarios prohibit the use of original datasets. However, DFQ solutions currently available suffer from lower accuracy, require synthetic data to calibration networks and are expensive in terms of time and cost. This research introduces SQuant, an on-the-fly DFQ framework that quantizes networks on inference-only devices with low computation and memory needs. Through the analysis of the second-order information of DNN task loss, the paper decomposes and approximates the Hessian-based optimization objective into three diagonal sub-items. These sub-items correspond to the three dimensions of weight tensor, such as element-wise, kernel-wise, and output channel-wise. The proposed method, named Constrained Absolute Sum of Error (CASE), minimizes the data-free optimization objective in the discrete domain without the need for any dataset and the awareness of network architecture. The research proposes an efficient algorithm with no backpropagation that decreases the computation complexity of the objective solver. With no fine-tuning and synthetic datasets, the proposed framework accelerates data-free quantization by achieving sub-second levels of quantization time and over 30% accuracy improvement compared to existing data-free post-training quantization works. SQuant framework is open-sourced at https://github.com/clevercool/SQuant.



---

