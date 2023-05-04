# How many bits does it take to quantize your neural network?

## Summary

Summary: This paper investigates the impact of quantization on a neural network's robustness to adversarial attacks. The researchers found that both robustness and non-robustness are not monotonic with the number of bits used for the representation, and neither are preserved by quantization from a real-numbered network. To address this issue, the paper introduces a verification method for quantized neural networks using SMT solving over bit-vectors to account for their exact, bit-precise semantics. The researchers built a tool to apply this method to a MNIST dataset classifier and demonstrated that it outperforms existing methods for analyzing real-numbered networks and quantized networks. The paper also shows how the number of bits in quantization can increase gender bias in a predictor for students' grades.


## Target Task

computer vision

## Content

<Abstract: Quantization converts neural networks into low-bit ﬁxed-point computations which can be carried out by eﬃcient integer-only hardware, and is standard practice for the deployment of neural networks on real-time embedded devices. We investigate how quantization aﬀects a network’s robustness to adversarial attacks, which is a formal veriﬁcation question. We show that neither robustness nor non-robustness are monotonic with changing the number of bits for the representation and, also, neither are preserved by quantization from a real-numbered network. For this reason, we introduce a veriﬁcation method for quantized neural networks which, using SMT solving over bit-vectors, accounts for their exact, bit-precise semantics. We built a tool and analyzed the eﬀect of quantization on a classiﬁer for the MNIST dataset. We demonstrate that, compared to our method, existing methods for the analysis of real-numbered networks often derive false conclusions about their quantizations, both when determining robustness and when detecting attacks, and that existing methods for quantized networks often miss attacks. Furthermore, we applied our method beyond robustness, showing how the number of bits in quantization enlarges the gender bias of a predictor for students’ grades.>



---

