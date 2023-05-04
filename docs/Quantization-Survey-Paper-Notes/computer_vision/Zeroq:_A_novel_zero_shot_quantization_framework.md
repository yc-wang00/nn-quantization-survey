# Zeroq: A novel zero shot quantization framework

## Summary

<Summary: > The paper introduces ZEROQ, a novel zero-shot quantization framework that enables mixed-precision quantization without training or validation data access by optimizing for a distilled dataset. The framework can support uniform and mixed-precision quantization, has low computational overhead and can complete the whole quantization process in less than 30 seconds. The proposed method was tested on various models and achieved higher accuracy compared to DFQ. The paper is open-sourced on GitHub.


## Target Task

computer vision

## Content

<Abstract: > Here is the abstract of the research paper "ZeroQ: A Novel Zero Shot Quantization Framework." The paper proposes a new zero-shot quantization framework called ZEROQ, which enables mixed-precision quantization without any access to the training or validation data. This is achieved by optimizing for a Distilled dataset, which matches the statistics of batch normalization across different layers of the network. ZEROQ can support both uniform and mixed-precision quantization. The paper tested the proposed method on a diverse set of models and achieved 1.71% higher accuracy on MobileNetV2, as compared to the recently proposed DFQ method. The framework has a very low computational overhead, and it can finish the entire quantization process in less than 30 seconds (0.5% of one epoch training time of ResNet50 on ImageNet). The paper is open-sourced on GitHub.



---

