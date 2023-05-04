# Normalization helps training of quantized LSTM

## Summary

<Summary: > The paper discusses how quantization can reduce the computational demands of long-short-term memory (LSTM) weights but the exploding gradient problem makes training difficult, especially with large weight matrices. The paper proposes that normalization techniques, such as weight normalization, layer normalization, and batch normalization, can help train quantized LSTMs by stabilizing the gradient magnitude. Normalized quantized LSTMs perform significantly better than unnormalized ones and are comparable to full-precision LSTMs in terms of performance while being smaller in size. The paper also identifies the limitations of existing quantization methods and the inefficiencies of the batch normalization extension.


## Target Task

speech recognition

## Content

<Abstract: > The paper discusses the use of quantization on long-short-term memory (LSTM) weights to reduce their computational demands. However, training a quantized LSTM is difficult due to the exploding gradient problem, especially when weight matrices are large. The paper shows that normalization techniques, such as weight normalization, layer normalization, and batch normalization, can stabilize the gradient magnitude and help train quantized LSTMs. Normalized quantized LSTMs perform significantly better than their unnormalized counterparts and are comparable to full-precision LSTMs in terms of performance while being much smaller in size. The paper also highlights the inefficiencies of existing quantization methods and the limitations of the batch normalization extension in storage and computational cost.



---

