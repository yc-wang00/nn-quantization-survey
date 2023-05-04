# Opq: Compressing deep neural networks with one-shot pruning-quantization

## Summary

Summary: The paper proposes a One-shot Pruning-Quantization (OPQ) method to compress and allocate compressions like sparsity and quantization codebook in neural networks that uses pre-trained model only. The paper suggests a unified channel-wise quantization method that enforces all channels to share a common codebook to reduce extra overhead in traditional channel-wise quantization. The experiments on AlexNet/MobileNet-V1/ResNet-50 show that OPQ method achieves high compression rates, more efficiency, and improved accuracy than the existing state-of-the-art methods.


## Target Task

computer vision

## Content

<Abstract: >As Deep Neural Networks (DNNs) usually are overparam-
eterized and have millions of weight parameters, it is chal-
lenging to deploy these large DNN models on resource-
constrained hardware platforms, e.g., smartphones. Numerous
network compression methods such as pruning and quant-
ization are proposed to reduce the model size signiﬁcantly,
of which the key is to ﬁnd suitable compression allocation
(e.g., pruning sparsity and quantization codebook) of each
layer. Existing solutions obtain the compression allocation in
an iterative/manual fashion while ﬁnetuning the compressed
model, thus suffering from the efﬁciency issue. Different
from the prior art, we propose a novel One-shot Pruning-
Quantization (OPQ) in this paper, which analytically solves
the compression allocation with pre-trained weight parame-
ters only. During ﬁnetuning, the compression module is ﬁxed
and only weight parameters are updated. To our knowledge,
OPQ is the ﬁrst work that reveals pre-trained model is suf-
ﬁcient for solving pruning and quantization simultaneously,
without any complex iterative/manual optimization at the
ﬁnetuning stage. Furthermore, we propose a uniﬁed channel-
wise quantization method that enforces all channels of each
layer to share a common codebook, which leads to low bit-
rate allocation without introducing extra overhead brought by
traditional channel-wise quantization. Comprehensive exper-
iments on ImageNet with AlexNet/MobileNet-V1/ResNet-50
show that our method improves accuracy and training efﬁ-
ciency while obtains signiﬁcantly higher compression rates
compared to the state-of-the-art.



---

