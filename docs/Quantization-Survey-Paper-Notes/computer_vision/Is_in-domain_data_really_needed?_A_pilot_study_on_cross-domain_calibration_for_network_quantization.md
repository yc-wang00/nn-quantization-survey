# Is in-domain data really needed? A pilot study on cross-domain calibration for network quantization

## Summary

<Summary: >This paper explores the possibility of using out-of-domain data to calibrate trained networks for post-training quantization. The results show that cross-domain calibration can result in stable performance of quantized models on multiple tasks in different image domains, suggesting that cross-domain knowledge can be borrowed for network quantization and compression.


## Target Task

computer vision

## Content

<Abstract:> Post-training quantization methods use a set of calibration data to compute quantization ranges for network parameters and activations. The calibration data usually comes from the training dataset which could be inaccessible due to sensitivity of the data. In this work, we want to study such a problem: can we use out-of-domain data to calibrate the trained networks without knowledge of the original dataset? We find cross-domain calibration leads to surprisingly stable performance of quantized models on 10 tasks in different image domains with 13 different calibration datasets. We believe our research opens the door to borrow cross-domain knowledge for network quantization and compression.



---

