# Adapt: fast emulation of approximate dnn accelerators in pytorch

## Summary

<Summary: >The paper introduces AdaPT, a PyTorch-based emulation framework that enables approximate inference and approximation-aware retraining. AdaPT is shown to be compatible with various DNN models and multipliers with different bitwidth values. The results demonstrated significant error recovery from approximate retraining and a reduced inference time of up to 53.9% compared to the baseline approximate implementation.


## Target Task

any task

## Content

<Abstract:> In this paper, the authors present AdaPT, a fast emulation framework that extends PyTorch to support approximate inference as well as approximation-aware retraining. AdaPT can be seamlessly deployed and is compatible with the most DNNs. The authors evaluate the framework on several DNN models and application fields including CNNs, LSTMs, and GANs for a number of approximate multipliers with distinct bitwidth values. The results show substantial error recovery from approximate retraining and reduced inference time up to 53:9 with respect to the baseline approximate implementation.



---

