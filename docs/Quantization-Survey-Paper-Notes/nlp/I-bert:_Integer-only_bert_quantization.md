# I-bert: Integer-only bert quantization

## Summary

<Summary: >This paper proposes I-BERT, a quantization scheme for Transformer-based models that utilizes integer-only arithmetic for the whole inference, unlike previous quantization schemes, which employ simulated quantization. The authors demonstrate that their method achieves similar or slightly higher accuracy compared to the full-precision baseline while providing a speedup of 2.4-4.0 for INT8 inference on a T4 GPU system as compared to FP32 inference.


## Target Task

nlp

## Content

<Abstract: >Transformer-based models such as BERT and RoBERTa have shown impressive performance in many NLP tasks. However, their memory footprint, inference latency, and power consumption make them inefficient for deployment at the edge or even in data centers, especially for real-time inference. One solution to this problem is quantization which compresses NN models by representing parameters and/or activations with low bit precision, such as 8-bit integer (INT8) instead of 32-bit floating-point (FP32). However, previous quantization schemes for Transformer based models use simulated quantization, which carries out operations using floating-point arithmetic during the inference, preventing efficient use of integer-only logical units. In this work, we propose I-BERT, a novel quantization scheme for Transformer-based models that uses only integer-only arithmetic for the entire inference. I-BERT uses lightweight integer-only approximation methods for nonlinear operations such as GELU, Softmax, and Layer Normalization. We evaluate I-BERT on GLUE downstream tasks using RoBERTa-Base/Large and show that I-BERT achieves similar (and slightly higher) accuracy compared to the full-precision baseline. Furthermore, our preliminary implementation of I-BERT shows a speedup of 2.4-4.0 for INT8 inference on a T4 GPU system as compared to FP32 inference. </Abstract:>



---

