# Accurate post training quantization with small calibration sets

## Summary

Summary: The paper proposes a post-training quantization method that optimizes parameters over the calibration set to minimize quantization errors of each layer separately, without significant accuracy degradation. The method suggests two flavors, parallel and sequential, for fixed and flexible bit-width allocation, respectively. The paper also suggests model global statistics tuning to correct biases introduced during quantization, yielding state-of-the-art results for both vision and text models. The suggested methods are much faster than the traditional Quantize Aware Training approach used for lower than 8-bit quantization. The code has been open-sourced.


## Target Task

computer vision

## Content

<Abstract: > Lately, post-training quantization methods have gained considerable attention, as they are simple to use, and require only a small unlabeled calibration set. This small dataset cannot be used to ﬁne-tune the model without signiﬁcant overﬁtting. Instead, these methods only use the calibration set to set the activations’ dynamic ranges. However, such methods always resulted in signiﬁcant accuracy degradation, when used below 8-bits (except on small datasets). Here we aim to break the 8-bit barrier. To this end, we minimize the quantization errors of each layer or block separately by optimizing its parameters over the calibration set. We empirically demonstrate that this approach is: (1) much less susceptible to overﬁtting than the standard ﬁne-tuning approaches, and can be used even on a very small calibration set; and (2) more powerful than previous methods, which only set the activations’ dynamic ranges. We suggest two ﬂavors for our method, parallel and sequential aim for a ﬁxed and ﬂexible bit-width allocation. For the latter, we demonstrate how to optimally allocate the bit-widths for each layer, while constraining accuracy degradation or model compression by proposing a novel integer programming formulation. Finally, we suggest model global statistics tuning, to correct biases introduced during quantization. Together, these methods yield state-of-the-art results for both vision and text models. For instance, on ResNet50, we obtain less than 1% accuracy degradation — with 4-bit weights and activations in all layers, but ﬁrst and last. The suggested methods are two orders of magnitude faster than the traditional Quantize Aware Training approach used for lower than 8-bit quantization. We open-sourced our code https://github.com/papers-submission/CalibTIP.



---

