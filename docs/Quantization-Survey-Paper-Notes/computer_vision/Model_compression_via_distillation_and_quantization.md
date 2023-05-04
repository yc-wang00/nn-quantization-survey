# Model compression via distillation and quantization

## Summary

Summary: This paper proposes two methods for compressing deep neural networks for resource-conscious environments, named quantized distillation and differentiable quantization. The proposed methods utilize weight quantization and distillation of larger networks into compressed student networks. The results of the experiments demonstrate that shallow quantized students can attain comparable accuracy to full-precision teacher models, with up to ten times compression and almost linear inference speedup with depth reduction.


## Target Task

computer vision

## Content

<Abstract: >This paper proposes two new compression methods for executing deep models in resource-constrained environments, such as mobile or embedded devices. The methods leverage weight quantization and distillation of larger networks, called “teachers,” into compressed “student” networks. The first method is called quantized distillation and incorporates distillation loss, expressed with respect to the teacher network, into the training of a smaller student network whose weights are quantized to a limited set of levels. The second method, differentiable quantization, optimizes the location of quantization points through stochastic gradient descent, to better fit the behavior of the teacher model. Experiments on convolutional and recurrent architectures show that quantized shallow students can reach similar accuracy levels to state-of-the-art full-precision teacher models, while providing up to order of magnitude compression, and inference speedup that is almost linear in the depth reduction.



---

