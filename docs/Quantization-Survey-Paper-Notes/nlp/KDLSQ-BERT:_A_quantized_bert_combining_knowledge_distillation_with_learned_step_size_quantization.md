# KDLSQ-BERT: A quantized bert combining knowledge distillation with learned step size quantization

## Summary

<Summary: >The paper proposes a novel quantization method named KDLSQ-BERT which combines knowledge distillation with learned step size quantization for language model quantization. The model was tested on GLUE benchmark and SQuAD and showcases effective performance, even outperforming existing BERT quantization methods while maintaining comparable performance to the full-precision baseline model with 14.9x compression ratio.


## Target Task

nlp

## Content

<Abstract: >Recently, transformer-based language models such as BERT have shown tremendous performance improvement for a range of natural language processing tasks. However, these language models usually are computation expensive and memory intensive during inference. To improve the inference performance, as well as reduce the model size while maintaining the model accuracy, we propose a novel quantization method named KDLSQ-BERT that combines knowledge distillation (KD) with learned step size quantization (LSQ) for language model quantization. The main idea of our method is that the KD technique is leveraged to transfer the knowledge from a ”teacher” model to a ”student” model when exploiting LSQ to quantize that ”student” model during the quantization training process. Extensive experiment results on GLUE benchmark and SQuAD demonstrate that our proposed KDLSQ-BERT not only performs effectively when doing different bit (e.g. 2-bit8-bit) quantization, but also outperforms the existing BERT quantization methods, and even achieves comparable performance as the full-precision base-line model while obtaining 14.9x compression ratio.



---

