# Neural Network Compression (Quantization ) for NLP 

### Task: 

- Language modeling 
- Name entity recognition 
- NMT (translation) 
- Question answering
- Sentiment analysis 
- Speech recognition 
- Textual entailment
- Word similarity 

### Model: 

Before transformer 

- LSTM, GRU, RNN based model

After transformer

- Bert-base (encoder), Transformer based
- LLM 



## Quantization Method: 

### PTQ: 

A quantization technique that is applied after the training process is completed. 

This means the model is first trained using high-precision (e.g., 32-bit) floating-point numbers, and then the weights of the trained model are quantized to lower precision, such as 8-bit integers.

### QAT: 

A method where the quantization process is incorporated into the training stage itself. 

This means the model is aware of the quantization process during training, and the loss function is modified to take into account the quantization error.

___



### Common Setting: 

8-bit quantization -> classic setting 

lower-bit quantization -> binary, ternary 



___



# Post Training Quantization for Large Language Model

### some takeaway 

1. asymmetric quantization > symmetric quantization 

2. WQ (weight-only quantization) > WAQ (weight and activation quantization) 

   - Robustness of Weight-only Quantization for Large Models

   - Challenge of Activation Quantization for Large Models



Quantization Method: (comparison in Microsoft paper. Full experiments)

1. RTN -> naive round-to-nearest baseline
2. GPTQ  https://arxiv.org/pdf/2210.17323.pdf
3. ZeroQuant  https://arxiv.org/pdf/2206.01861.pdf

Other methods:

1. Smooth Quant https://arxiv.org/pdf/2211.10438.pdf

2. LLM.int8() https://arxiv.org/pdf/2208.07339.pdf

3. RPTQ https://arxiv.org/pdf/2304.01089.pdf

   



A Comprehensive Study on Post-Training Quantization for Large Language Models

Microsoft 

https://arxiv.org/pdf/2303.08302.pdf

