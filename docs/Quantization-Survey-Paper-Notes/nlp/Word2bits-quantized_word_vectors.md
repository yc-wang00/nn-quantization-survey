# Word2bits-quantized word vectors

## Summary

<Summary: >The paper proposes a method called Word2Bits to learn high-quality quantized word vectors using 1-2 bits per parameter, which reduces the storage and acts as a regularizer against overfitting. The experiments show that their method outperforms full precision word vectors on standard word similarity tasks and question answering while taking up only 8-16x less space. Word2Bits introduces a quantization function into the Word2Vec loss formulation.


## Target Task

nlp

## Content

<Abstract: >Word vectors are used extensively in deep learning models for natural language processing, but they require a significant amount of memory and storage. In this paper, we propose a method to learn high-quality quantized word vectors using 1-2 bits per parameter, which not only reduces the required storage but also acts as a regularizer against overfitting. Our experiments show that our quantized word vectors outperform full precision word vectors on standard word similarity tasks and question answering while taking up only 8-16x less space. Our method, called Word2Bits, introduces a quantization function into the Word2Vec loss formulation.



---

