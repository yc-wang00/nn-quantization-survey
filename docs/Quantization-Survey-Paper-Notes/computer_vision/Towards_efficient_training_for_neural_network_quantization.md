# Towards efficient training for neural network quantization

## Summary

Summary: The paper proposes a technique named scale-adjusted training (SAT) to address the accuracy drop resulting from performance degeneration in quantization, due to reduced capacity or inefficient training. The authors identified two critical rules for efficient training and recommend compliance with them while avoiding popular parameterized clipping activation (PACT) technique, which introduces quantization error while calculating gradient. SAT and gradient-calibrated PACT help achieve comparable or better performance on quantized models than full-precision ones, with consistent improvement over previous quantization methods across multiple models.


## Target Task

computer vision

## Content

<Abstract: >
Quantization is a promising method to deploy computation-intensive deep models into resource-constrained platforms, but it suffers from performance degeneration. To investigate whether the accuracy drop is due to the reduced capacity or the inefﬁcient training during the quantization procedure, two critical rules for efﬁcient training are discovered. Recent quantization approaches violate these rules and lead to degenerated convergence. To deal with this problem, the authors propose a simple yet effective technique, named scale-adjusted training (SAT), to comply with the discovered rules and facilitate efﬁcient training. The authors also analyze the quantization error introduced in calculating the gradient in the popular parameterized clipping activation (PACT) technique. Through SAT together with gradient-calibrated PACT, quantized models obtain comparable or even better performance than their full-precision counterparts, achieving state-of-the-art accuracy with consistent improvement over previous quantization methods on a wide spectrum of models.



---

