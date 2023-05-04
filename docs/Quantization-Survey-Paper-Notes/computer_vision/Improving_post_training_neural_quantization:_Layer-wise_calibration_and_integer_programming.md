# Improving post training neural quantization: Layer-wise calibration and integer programming

## Summary

Summary: The article discusses post-training quantization methods that have gained attention due to their simplicity and requirement of a small unlabeled calibration set. However, such methods result in accuracy degradation below 8-bits. The article proposes minimizing quantization errors of each layer separately by optimizing its parameters over the calibration set, which is less susceptible to over-fitting and more powerful than previous methods. The article also suggests optimal allocation of bit-widths for each layer and model global statistics tuning to correct biases introduced during quantization, resulting in state-of-the-art results for both vision and text models, with less than 1% accuracy degradation on ResNet50 with 4-bit weights and activations in all layers except the smallest two.


## Target Task

computer vision

## Content

<Abstract: >Lately, post-training quantization methods have gained considerable attention, as
they are simple to use, and require only a small unlabeled calibration set. This
small dataset cannot be used to ﬁne-tune the model without signiﬁcant over-ﬁtting.
Instead, these methods only use the calibration set to set the activations’ dynamic
ranges. However, such methods always resulted in signiﬁcant accuracy degradation,
when used below 8-bits (except on small datasets). Here we aim to break the 8-bit
barrier. To this end, we minimize the quantization errors of each layer separately
by optimizing its parameters over the calibration set. We empirically demonstrate
that this approach is: (1) much less susceptible to over-ﬁtting than the standard
ﬁne-tuning approaches, and can be used even on a very small calibration set; and
(2) more powerful than previous methods, which only set the activations’ dynamic
ranges. Furthermore, we demonstrate how to optimally allocate the bit-widths
for each layer, while constraining accuracy degradation or model compression by
proposing a novel integer programming formulation. Finally, we suggest model
global statistics tuning, to correct biases introduced during quantization. Together,
these methods yield state-of-the-art results for both vision and text models. For
instance, on ResNet50, we obtain less than 1% accuracy degradation — with 4-bit
weights and activations in all layers, but the smallest two. We open sourced our
code.



---

