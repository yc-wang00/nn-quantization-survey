# Revisiting the calibration of modern neural networks

## Summary

<Summary: > The paper focuses on the importance of accurate estimation of predictive uncertainty in neural networks for safe application. The authors revisit the question of model calibration and accuracy in recent state-of-the-art image classification models. They find that newer models not using convolutions are well-calibrated, and the trends observed in prior models such as decay of calibration with distribution shift or model size are less pronounced in recent architectures. The study suggests that architecture plays a major role in determining calibration properties.


## Target Task

computer vision

## Content

<Abstract: >Accurate estimation of predictive uncertainty (model calibration) is essential for the safe application of neural networks. Many instances of miscalibration in modern neural networks have been reported, suggesting a trend that newer, more accurate models produce poorly calibrated predictions. Here, we revisit this question for recent state-of-the-art image classification models. We systematically relate model calibration and accuracy, and find that the most recent models, notably those not using convolutions, are among the best calibrated. Trends observed in prior model generations, such as decay of calibration with distribution shift or model size, are less pronounced in recent architectures. We also show that model size and amount of pretraining do not fully explain these differences, suggesting that architecture is a major determinant of calibration properties.



---

