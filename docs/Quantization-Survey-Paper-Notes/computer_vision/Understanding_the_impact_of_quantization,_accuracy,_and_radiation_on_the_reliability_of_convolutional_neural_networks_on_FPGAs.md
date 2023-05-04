# Understanding the impact of quantization, accuracy, and radiation on the reliability of convolutional neural networks on FPGAs

## Summary

Summary: The paper analyzes the impact of binary quantization on the convolutional layers of neural networks on FPGAs in terms of radiation cross-section, model accuracy, resource utilization, and error criticality. The design with quantized convolutional layers can be 39% less sensitive to radiation, and the portion of errors considered critical in the network is increased by 12%. Generic equations are derived to model the overall failure rate of neural networks. The Modified National Institute of Standards and Technology (MNIST) CNN is used as a case study to evaluate trade-offs between various factors. Fault injection experiments are conducted to determine which portions of the CNN’s circuit generate tolerable or critical errors due to the vulnerability of the feature extraction phase, and the error rate in a given radiation environment is estimated using experimental data.


## Target Task

computer vision

## Content

<Abstract:>
Convolutional neural networks (CNNs) implemented on field-programmable gate arrays (FPGAs) are becoming promising solutions for safety-critical applications. However, radiation-induced errors, such as single-event upsets (SEUs), can affect the reliability of static random-access memory (SRAM)-based FPGAs. In this paper, we analyze the impact of binary quantization on the convolutional layers of neural networks on FPGAs, especially in terms of radiation cross-section, model accuracy, resource utilization, and error criticality. We find that a design with quantized convolutional layers can be 39% less sensitive to radiation, and the portion of errors considered critical in the network is increased by 12%. Additionally, we derive generic equations that consider both accuracy and radiation in order to model the overall failure rate of neural networks. We use a case study of the Modified National Institute of Standards and Technology (MNIST) CNN to evaluate the trade-offs between various factors. Through extensive fault injection experiments, we determine which portions of the CNN’s circuit are more likely to generate tolerable or critical errors at the output due to the vulnerability of the feature extraction phase. We also estimate the error rate in a given radiation environment using experimental data.



---

