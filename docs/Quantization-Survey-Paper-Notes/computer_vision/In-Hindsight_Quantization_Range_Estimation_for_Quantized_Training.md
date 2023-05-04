# In-Hindsight Quantization Range Estimation for Quantized Training

## Summary

<Summary: >This paper discusses how quantization of neural networks is an effective technique for faster and efficient execution on low-resource devices. The paper further explores the effectiveness of fully quantized training, such as quantizing backpropagation, and identifies effective gradient quantization as an open problem. The authors propose an alternative to dynamic quantization, called in-hindsight range estimation, which enables fast static quantization of gradients and activations, requiring minimal hardware support, and can be used with other advances in quantized training. The authors compare their method to existing ones and demonstrate its effectiveness with various architectures.


## Target Task

computer vision

## Content

<Abstract: >Quantization techniques applied to the inference of deep
neural networks have enabled fast and efﬁcient execution
on resource-constraint devices. The success of quantiza-
tion during inference has motivated the academic commu-
nity to explore fully quantized training, i.e. quantizing back-
propagation as well. However, effective gradient quanti-
zation is still an open problem. Gradients are unbounded
and their distribution changes signiﬁcantly during training,
which leads to the need for dynamic quantization. As we
show, dynamic quantization can lead to signiﬁcant memory
overhead and additional data trafﬁc slowing down train-
ing. We propose a simple alternative to dynamic quanti-
zation, in-hindsight range estimation, that uses the quanti-
zation ranges estimated on previous iterations to quantize
the present. Our approach enables fast static quantization
of gradients and activations while requiring only minimal
hardware support from the neural network accelerator to
keep track of output statistics in an online fashion. It is in-
tended as a drop-in replacement for estimating quantization
ranges and can be used in conjunction with other advances
in quantized training. We compare our method to existing
methods for range estimation from the quantized training
literature and demonstrate its effectiveness with a range of
architectures, including MobileNetV2, on image classiﬁca-
tion benchmarks (Tiny ImageNet & ImageNet).



---

