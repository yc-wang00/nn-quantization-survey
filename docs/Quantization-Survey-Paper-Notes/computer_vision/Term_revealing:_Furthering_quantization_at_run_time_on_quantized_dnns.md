# Term revealing: Furthering quantization at run time on quantized dnns

## Summary

Summary: This paper presents a new technique called Term Revealing (TR) that further improves quantization in Deep Neural Networks (DNNs) by operating on power-of-two terms and selecting a fixed number of largest terms at runtime. It has minimal impact on DNN model performance and is used to facilitate tightly synchronized processor arrays for efficient parallel processing. An FPGA implementation is developed that can switch between conventional quantization and TR-enabled quantization with negligible delay. The paper uses a signed digit representation (SDR) to enhance TR's efficiency and shows significant reductions in inference computations compared to conventional quantization with the same level of model performance, evaluated on MLR for MNIST, multiple CNNs for Imagenet, and an LSTM for Wikitext-2.


## Target Task

computer vision

## Content

<Abstract:>
We present a novel technique called Term Revealing (TR) for furthering quantization at run time in Deep Neural Networks (DNNs) already quantized with conventional quantization methods for improved performance. TR operates on power-of-two terms in binary expressions of values and selects a fixed number of largest terms at runtime in computing a dot-product computation. By exploiting normal-like weight and data distributions, TR has minimal impact on DNN model performance. We use TR to facilitate tightly synchronized processor arrays for efficient parallel processing. We show an FPGA implementation that can use a small number of control bits to switch between conventional quantization and TR-enabled quantization with negligible delay. To enhance TR's efficiency further, we use a signed digit representation (SDR), and we develop an efficient encoding method called Hybrid Encoding for Signed Expressions (HESE). We evaluate TR with HESE encoded values on an MLP for MNIST, multiple CNNs for ImageNet, and an LSTM for Wikitext-2 and show significant reductions in inference computations compared to conventional quantization for the same level of model performance.



---

