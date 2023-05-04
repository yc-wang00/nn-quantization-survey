# Zero-shot adversarial quantization

## Summary

Summary: The paper proposes a zero-shot adversarial quantization (ZAQ) framework which allows effective knowledge transfer from a full-precision model to its quantized model without accessing training data. The framework uses a novel two-level discrepancy modeling to synthesize informative and diverse data examples and optimize the quantized model in an adversarial learning fashion. The experiments on three vision tasks show the superiority of ZAQ over strong zero-shot baselines and validate its main components.


## Target Task

computer vision

## Content

<Abstract: >
Model quantization is an effective approach to compress deep neural networks for deployment on mobile and edge devices. However, traditional methods for fine-tuning quantized models require access to training datasets, making them inapplicable in real situations where data privacy and security are concerns. To address this issue, we propose a zero-shot adversarial quantization (ZAQ) framework that facilitates effective discrepancy estimation and knowledge transfer from a full-precision model to its quantized model without accessing training data. ZAQ achieves this using a novel two-level discrepancy modeling to drive a generator to synthesize informative and diverse data examples to optimize the quantized model in an adversarial learning fashion. We conduct extensive experiments on three fundamental vision tasks, demonstrating the superiority of ZAQ over strong zero-shot baselines and validating the effectiveness of its main components.



---

