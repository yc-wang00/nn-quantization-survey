# Introduction

Natural Language Processing (NLP) has witnessed dramatic progress over the last few decades, moving from simple rule-based systems to complex deep learning models capable of understanding and generating human language with impressive accuracy. As these models have evolved, so too has the need for efficient ways to deploy them. One such method is quantization, a technique used to reduce the computational and memory requirements of these models without significantly sacrificing their performance.

Quantization in NLP involves converting the continuous weights of a model into discrete counterparts. This reduces the memory footprint and computational requirements, making the models faster and more efficient, particularly important for deployment on devices with limited resources. The process, however, is non-trivial as it poses a challenge: maintaining the balance between the model's efficiency and its performance.

This document explores the evolution of quantization techniques in NLP, focusing on the era before and after the introduction of Transformer models. It further dissects the timeline after the advent of Large Language Models (LLMs), as these massive models pose their unique challenges and opportunities for quantization.

We will delve into the various quantization techniques and their evolution, performance, and associated research, starting from pre-Transformer NLP models like Long Short-Term Memory (LSTM) to Transformer-based models like BERT, and moving towards the recent and more complex LLMs. The document also includes exploration of some notable studies and research papers for a detailed understanding of these techniques.

By providing an organized compilation of these techniques and their chronological evolution, this document aims to offer a comprehensive guide to the landscape of quantization in NLP. The goal is not just to reflect on the strides that have been made in the field, but also to anticipate future trends and opportunities. Let's embark on this journey through the past, present, and potential future of quantization methods in NLP.



# Pre-Transformer 

In the Pre-Transformer era, several methods were used to process and understand text data. Techniques such as Bag of Words (BoW), TF-IDF, and n-grams were early text representation methods, which were then significantly enhanced by the introduction of word embeddings like Word2Vec and GloVe. The introduction of Recurrent Neural Networks (RNNs), and more specifically, architectures like Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU), brought about a revolutionary change in the NLP field, enabling models to understand the sequence and context in language data.

## Model Structure 

### RNN

List out RNN 

### LSTM in NLP

LSTM, a special kind of RNN, was capable of learning long-term dependencies, which was a significant leap forward from the simple, feed-forward networks. It was particularly effective in applications such as language modeling, machine translation, text generation, and named entity recognition.

- "Long Short-Term Memory", Hochreiter & Schmidhuber (1997): The paper introduced the LSTM architecture. [Link](http://www.bioinf.jku.at/publications/older/2604.pdf)
- "Sequence to Sequence Learning with Neural Networks", Sutskever et al. (2014): This paper demonstrated the application of LSTMs in sequence-to-sequence tasks, providing the backbone for numerous NLP tasks. [Link](https://arxiv.org/abs/1409.3215)

#### Limitations of LSTM

Despite LSTM's effectiveness in understanding sequence and context, it came with its own set of challenges. The recurrent nature of LSTM made it computationally expensive and slow to train. Furthermore, LSTM's memory cell could capture dependencies over a certain range but struggled with very long sequences, leading to difficulties in learning overall structure in the data.

## Quantization Methods Application

As LSTM models and other neural networks grew in complexity, the need for memory-efficient and computationally efficient models became evident. This need led to the exploration of quantization methods, which aimed at reducing the precision of the weights in a neural network, hence reducing the memory footprint and computational requirements.

Some of the early quantization methods that came into the picture  K-means Quantization, and Binary Quantization. Here we divided the section in binary/ternary quantization and general k-bit quantization 

#### Binary and Ternary Quantization

- Binary quantization uses only 1 bit to represent weights. Methods include deterministic binarization, stochastic binarization, and loss-aware binarization. However, binarization generally leads to large drops in accuracy.
- Ternary quantization uses 2 bits to represent weights as -1, 0, or +1. Methods include simple threshold-based ternarization, trainable ternarization, and hybrid schemes like HitNets. Ternary quantization works better than binary for many models.

#### General k-bit Quantization

- Uniform quantization divides the weight range into equal intervals. It is easy to implement but suboptimal for non-uniform weight distributions.
- Balanced quantization partitions weights into equal sized bins based on percentiles. This better utilizes the full range.
- K-means clustering is used in techniques like product quantization and residual quantization to perform non-uniform quantization.
- Loss-aware quantization directly optimizes the quantization parameters to minimize the overall network loss. This works better than static post-training quantization.

## Results

![image-20230713130105107](/home/titan-yc/.config/Typora/typora-user-images/image-20230713130105107.png)

Ref. Compression of Deep Learning Models for Text: A Survey[https://arxiv.org/pdf/2008.05221.pdf]

## Summary 

- Binary quantization does not work well for text models like RNNs and LSTMs. It leads to exploding/vanishing gradients.
- Ternary quantization with 2 bits provides a good balance of compression and accuracy for text models. Hybrid schemes like HitNets combine ternary and binary quantization across layers.
- For RNNs, threshold-based ternary quantization works better for weights while stochastic ternary quantization works better for activations based on their distribution.
- Quantizing both embeddings and weights during training works better than post-training quantization for text models.
- Loss-aware quantization optimized during training outperforms static post-training quantization for text models.

In summary, quantization can effectively compress text models but RNNs/LSTMs require more than 1-bit quantization. Ternary quantization works well for general text models while mixed-precision schemes optimized during training give best results for Transformers. This will be discussed in the transformer era section. 



# Transformer Era

The introduction of the Transformer architecture in 2017 marked a turning point in the field of NLP. Vaswani et al. proposed this novel architecture in the paper "Attention is All You Need" as a remedy to the limitations faced by its RNN predecessors like LSTM and GRU. The advent of Transformer models in NLP introduced architectures with much higher complexity and significantly larger parameter space compared to their predecessors. 

## Introduction of Transformer Architecture

Transformer models deviate from the recurrent nature of LSTMs and GRUs, introducing the concept of "attention" which allows the model to focus on different parts of the input sequence when producing an output. This attention mechanism, specifically the self-attention or scaled dot-product attention, enables Transformers to handle long-term dependencies effectively and makes them highly parallelizable, speeding up training times significantly.

However, despite these improvements, Transformer models, due to their increased complexity and large number of parameters, require substantial computational resources. This has implications for their deployment, especially in resource-constrained environments.

Reference 

- "Attention is All You Need", Vaswani et al. (2017): The paper that introduced the Transformer model. [Link](https://arxiv.org/abs/1706.03762)

__Impact on Quantization Methods__

With the advent of Transformer models, the need for efficient quantization methods became even more pronounced. The large number of parameters in these models necessitated the development of novel quantization techniques that could reduce the model size without significantly affecting performance.

## Emergence of BERT and Its Implications

One notable Transformer-based model is BERT (Bidirectional Encoder Representations from Transformers), which revolutionized NLP by providing significant improvements in performance across various tasks. BERT's large size, particularly in its larger variants, presented further challenges for deployment, providing an impetus for the development of specific quantization techniques for Transformer models.

Reference 

- "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding", Devlin et al. (2018): The original paper introducing BERT. [Link](https://arxiv.org/abs/1810.04805)

## Quantization Techniques for Transformers

Before the advent of LLMs, several quantization techniques were proposed to deal with the increased size and complexity of Transformer models. These techniques took into account the specific architecture of these models, optimizing different aspects to balance efficiency and performance.

Here are 

#### I-BERT: Integer-only BERT Quantization

I-BERT converts all the floating-point weights in the BERT model into integer values. This method simplifies the hardware requirements and reduces memory usage. I-BERT uses a non-uniform quantization algorithm that performs comparably to full-precision BERT on GLUE benchmark tasks.

#### Q-BERT: Hessian Based Ultra Low Precision Quantization of BERT

Q-BERT introduces Hessian-based quantization, which uses second-order information to identify optimal bit-width allocation across layers. This method ensures efficient use of memory while maintaining a competitive performance.

#### Efficient 8-Bit Quantization of Transformer Neural Machine Language Translation Model

This paper proposes an 8-bit quantization method specific to Transformer models, reducing the model size and accelerating the inference speed without significant performance drop. This method is particularly effective for NMT (Neural Machine Translation) tasks.

#### MKQ-BERT: QUANTIZED BERT WITH 4BITS WEIGHTS AND ACTIVATIONS

#### BinaryBERT: Pushing the Limit of BERT Quantization

Reference

- "Integer-only BERT Quantization", Kim et al. (2021): [Link](https://arxiv.org/pdf/2101.01321.pdf)

- "Q-BERT: Hessian Based Ultra Low Precision Quantization of BERT", Shen et al. (2020): [Link](https://ojs.aaai.org/index.php/AAAI/article/view/6409)
- "Efficient 8-Bit Quantization of Transformer Neural Machine Language Translation Model", Lin et al. (2019): [Link](https://arxiv.org/pdf/1906.00532.pdf)

## Summary

Each of these methods has its strengths and weaknesses. For instance, I-BERT and Q-BERT can reduce model size significantly, but they might experience a slight performance degradation. On the other hand, the efficient 8-bit quantization method for Transformer models achieves good balance between model size reduction and performance preservation, but it may not achieve as high a compression ratio as the other two methods.

Ultimately, the choice between these methods depends on the specific needs of the application, including available resources and performance requirements.

Despite the introduction of quantization, these methods have demonstrated that it's possible to maintain a competitive performance level. For example, I-BERT achieves performance comparable to full-precision BERT on the GLUE benchmark, Q-BERT shows only minimal performance degradation across several NLP tasks, and the 8-bit quantization approach maintains strong performance in NMT tasks.



- For Transformers, mixed precision quantization with different bits for different layers/heads works better than blanket quantization.
- Word embeddings can be quantized to 2-4 bits with minimal impact on downstream tasks.
- Overall, ternary quantization provides a good tradeoff for general text models. Loss-aware mixed precision quantization gives state-of-the-art results for Transformers like BERT.
- The Transformer architecture is highly robust to quantization compared to other text models like RNNs.
- more keypoints....

In summary, the Transformer era brought about a new set of challenges and opportunities in quantization methods for NLP. As these models continue to evolve and increase in complexity, the development and refinement of quantization methods remain an active area of research.



# LLM Era

LLM, standed for Large Language Model, refers to a category of NLP models that have a large number of parameters. They are trained on extensive text corpora and are capable of understanding context, generating human-like text, and demonstrating a deep understanding of many different topics.

The term 'Large' in LLMs is indicative of the sheer size of these models in terms of their parameter counts. For instance, GPT-3, one of the largest models to date, has 175 billion parameters. This significant increase in parameters has resulted in models with much higher complexity and accuracy compared to their predecessors, leading to a new era in NLP, often referred to as the 'LLM Era'.

The LLM Era is generally considered to have begun around the time when models started to scale beyond a billion parameters, which happened around 2018-2019 with the advent of models like GPT-2, MegatronLM, and subsequently, GPT-3.

Nowadays, with the rapid incresed popularity of chatgpt, there are a list of LLMs which contains  hundreds of billions of parameters come up in this field such as Jurassic-1, Megatron-Turing, LaMDA, BLOOM, Claude, and so on. 

Their large size allows them to capture more nuanced patterns in the data and generate more contextual outputs. They have been shown to perform exceptionally well on a range of NLP tasks, from translation to text generation, and even tasks they were not explicitly trained on, a phenomenon known as 'zero-shot' learning.

However, the larger the model, the more computational resources it requires. This includes both the resources needed to train the model and to use the model for inference. The large size also makes it challenging to deploy these models on resource-constrained devices, such as mobile phones or embedded systems. This is why quantization methods have become increasingly important in the LLM Era, as they allow for the reduction of model size and computational requirements while attempting to maintain high model performance.



## General quantization setup for LLM 

A general quantization setup for language model can be divided into PTQ and QAT.

### **Post-Training Quantization (PTQ):**

Post-training quantization, as the name suggests, is a technique where quantization is applied after the model has been fully trained using high-precision floating point weights and activations. The key steps in PTQ are:

- Train the model to completion using floating point (32-bit or higher precision) numbers. This allows the model to converge to an accurate set of weights and activations.
- Analyze the distribution of weights and activations after training to select optimal quantization parameters like bit-widths, clipping values etc.
- Quantize the weights and activations by replacing the floating point values with low-precision integer equivalents using the selected quantization parameters. For example, converting 32-bit floats to 8-bit integers.
- Fine-tune the quantized model to recover any small loss in accuracy. This fine-tuning is usually fast and uses low learning rates.

The benefits of post-training quantization include simplicity and convenience, since quantization is treated as an after-thought. But the drawback is that there can be a larger loss in model accuracy compared to quantization-aware training.

### **Quantization-Aware Training (QAT):**

In QAT, the model is aware of quantization and its effects right from the start of training. The key aspects are:

- Quantization operations like rounding and clamping are simulated during training. This allows the model to learn parameters that are robust to quantization loss.
- The training loss function is modified to include quantization error as a term, so the model can directly learn to minimize this error.
- Quantization parameters like bit-widths are dynamically learned during training by observing activation distributions.
- Batch normalization folding merges batch norm parameters into weights before quantization.

#### PTQ or QAT? Which one is better? 

The benefits of QAT include better accuracy compared to PTQ, and the ability to learn optimal quantization bit-widths. The challenges include increased training time and complexity. Thus in the context of LLM, receby research has favored post-training quantization (PTQ) over quantization-aware training (QAT) for compressing large language models (LLMs). PTQ allows quantizing a pre-trained floating point model to lower precisions without additional training. In contrast, QAT jointly trains the model to learn lower precision weights and activations. While QAT can achieve better accuracy, it requires full re-training which is prohibitively expensive for large models. For example, training a model like GPT-3 with 175 billion parameters on thousands of GPUs for months would need to be repeated for QAT. PTQ avoids this computational burden by quantizing the already trained model with minimal data and tuning. Consequently, PTQ has emerged as a more practical solution for deploying production LLMs with reduced precision. The focus is now on developing PTQ methods that can maximize compression without significant accuracy loss.



### Quantization Method for LLM: 

Recent research has explored techniques to optimize large language models (LLMs) using post-training quantization to reduce model size and computational costs. A comprehensive study by Yao et al. (2023) evaluates different quantization schemes and granularities using methods like GPTQ and ZeroQuant across a range of model sizes.

### GPTQ

GPTQ introduces a new quantization method specifically designed for GPT models. This technique ensures that quantization can be applied without significant loss of performance.

### ZeroQuant

ZeroQuant presents a novel approach to quantization that focuses on zero-valued weights in neural networks. By doing so, it enables more efficient use of memory and computational resources.

### LLM.int8()

This paper proposes a method to reduce the precision of weights in LLMs to 8 bits, which allows for substantial reduction in the memory footprint of these models.

### RPTQ

RPTQ offers a method for Re-training Post-training Quantization, a two-step process that first quantizes the model weights, and then retrains the quantized model to restore the performance.

### SmoothQuant

SmoothQuant introduces a new approach to quantization, which uses probabilistic rounding schemes to maintain high performance while reducing the memory and computational needs.

Reference

- "GPTQ: Quantization for Large Language Models", Sharma et al. (2022): [Link](https://arxiv.org/pdf/2210.17323.pdf)

- "ZeroQuant: Rethinking Quantization for Large Language Models", Shen et al. (2022): [Link](https://arxiv.org/pdf/2206.01861.pdf)
- "LLM.int8(): Low Precision Large Language Models", Bhandare et al. (2022): [Link](https://arxiv.org/pdf/2208.07339.pdf)
- "Re-training Post-training Quantization for Large Language Models", Zhang et al. (2023): [Link](https://arxiv.org/pdf/2304.01089.pdf))
- "SmoothQuant: Smoothing the path to low-precision large language models", Ambroladze et al. (2022): [Link](https://arxiv.org/pdf/2211.10438.pdf)



## Summary 

These quantization methods offer a variety of approaches to reducing the resource requirements of LLMs, making these models more accessible for deployment on various hardware platforms. As these models continue to evolve and increase in size and complexity, the need for efficient and effective quantization methods will only continue to grow.

Some key findings in comparison between all methods:

- - Activation quantization is more challenging than weight quantization, with smaller models showing better tolerance.
  - Different model families behave differently - BLOOM has no divergence issues but OPT struggles beyond 6.7B parameters.
  - Current methods can't achieve full model quality with 4-bit weights or 4-bit weights + 8-bit activations.
  - Fine-grained quantization recovers model quality for >13B models but still not optimal.
  - LoRC provides substantial gains, especially for lower bit precision, and recovers close to full model quality.



NOTICE THERE ARE MORE PAPER IN THE TODO LIST.
