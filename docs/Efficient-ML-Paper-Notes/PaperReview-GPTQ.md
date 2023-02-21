# GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers 

## Info: 
- ___Date Submitted____:  31 Oct 2022
- ___Topic___: #quantization, #transformer, #efficient-ml 
- ___PDFLink___: [[GPTQ.pdf]] 
- ___CodeLink___: https://github.com/IST-DASLab/gptq

## Summary:  

The paper discusses "GPTQ", a one-shot weight quantization method for the Generative Pre-trained Transformer (GPT) models. GPT models are known for their high performance on language modeling tasks, but they are also known for their high computational and storage costs. The new method can quantize GPT models with 175 billion parameters in approximately four GPU hours, reducing the bitwidth down to 3 or 4 bits per weight, with negligible accuracy degradation compared to the uncompressed baseline. It more than doubles the compression gains relative to previously-proposed one-shot quantization methods, allowing to execute an 175 billion-parameter model inside a single GPU. They also show experimentally that these improvements can be leveraged for end-to-end inference speedups.

## Result/Achievement:

The author/s present GPTQ, an approximate second-order method for quantizing large language models. **Their method is capable of compressing the largest publicly-available language models to an average of 2.5-4 bits per component with low accuracy loss.** This leads to significant usability improvements and end-to-end speedups. 

#### Compare with Rounding To the Nearest(RTN) 

![[Pasted image 20230109222132.png]]

Choose RTN as a baseline because this is currently the method of choice in all works on quantization of very large language models such as: ZeroQuant [TODO: REVIEW], LLM.int8() [TODO: REVIEW], and nuQmm [TODO: REVIEW] (Notice these are one-shot post-training quantization methods)

More accurate methods, such as AdaRound [TODO: REVIEW] or BRECQ  [TODO: REVIEW], are currently far too slow for models with many billions of parameters. 

From the graph, we can see GPTQ is able to maintain good performace on most tasks at 3-bit while RTN collapses. Sometimes it actually further improved accuracy via finer-granularity grouping/bucketing as shown in the following table:

![[Pasted image 20230109222954.png]]

Besides maintaining the accuracy, it also provides practical speed-up and huge model compression due to the nature of its setup as shown in the following table:

![[Pasted image 20230109223304.png]]

Unlike LLM.int8(), which reduces memory costs but has the same runtime as the FP16 baseline, they show that their quantized models can achieve significant speedups for this application. For language generation, the model processes and outputs one token at-a-time, which for OPT-175B can easily take a few 100s of milliseconds per token.

## Interesting ideas/Takeaway: 

1. LLM.int8() reduced memory cost but has the same runtime, doesn't provide actual speed-up
2. GPTQ can speed up the movement of memory operation, but not ablt to speed up the actual matrix multiplications, due to the lack of direct hardware support for mixed-precision operands (e.g. FP16 × INT4)
3. GPTQ make quantizing and inferencing a 175B parameters LLM possible on a single A100(80GB Ram)


## Personal Note: 

1. 175B parameters LLM can be inferered in one A100, which will save a huge cost for a lot of users. 
2. Still need to understand the core algorithm. (By looking at the source code)
3. would be cool if try to run their experiment to see if everything is acheiveable. 

