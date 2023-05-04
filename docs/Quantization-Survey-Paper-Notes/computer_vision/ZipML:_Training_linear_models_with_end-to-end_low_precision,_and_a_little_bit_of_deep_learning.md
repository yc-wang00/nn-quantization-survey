# ZipML: Training linear models with end-to-end low precision, and a little bit of deep learning

## Summary

Summary: The paper discusses training machine learning models with reduced precision, which can significantly reduce computation and communication. The authors focus on linear models and propose a simple framework called ZipML based on double sampling, which can execute training at low precision with no bias and guarantee convergence. The framework is validated across a range of applications and can lead to speedups of up to 6.5 times compared to full 32-bit precision. The authors also propose a variance-optimal stochastic quantization strategy that can save up to 1.7 times in data movement compared with uniform quantization, and achieve higher accuracy than state-of-the-art XNOR-Net when training deep networks with quantized models.


## Target Task

computer vision

## Content

<Abstract: Recently there has been signiﬁcant interest in
training machine-learning models at low preci-
sion: by reducing precision, one can reduce com-
putation and communication by one order of
magnitude. We examine training at reduced pre-
cision, both from a theoretical and practical per-
spective, and ask: is it possible to train models
at end-to-end low precision with provable guar-
antees? Can this lead to consistent order-of-
magnitude speedups? We mainly focus on linear
models, and the answer is yes for linear models.
We develop a simple framework called ZipML
based on one simple but novel strategy called
double sampling. Our ZipML framework is able
to execute training at low precision with no bias,
guaranteeing convergence, whereas naive quanti-
zation would introduce signiﬁcant bias. We val-
idate our framework across a range of applica-
tions, and show that it enables an FPGA proto-
type that is up to 6:5faster than an implemen-
tation using full 32-bit precision. We further de-
velop a variance-optimal stochastic quantization
strategy and show that it can make a signiﬁcant
difference in a variety of settings. When applied
to linear models together with double sampling,
we save up to another 1:7in data movement
compared with uniform quantization. When
training deep networks with quantized models,
we achieve higher accuracy than the state-of-the-
art XNOR-Net.>



---

