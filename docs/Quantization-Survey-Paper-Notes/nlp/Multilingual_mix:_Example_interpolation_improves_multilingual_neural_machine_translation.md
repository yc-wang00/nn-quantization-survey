# Multilingual mix: Example interpolation improves multilingual neural machine translation

## Summary

Summary: The paper introduces a multilingual crossover encoder-decoder to fuse language pairs at an instance level. Their approach interpolates instances from different language pairs into joint ‘crossover examples’ to encourage sharing input and output spaces across languages. They propose techniques to improve example interpolation across dissimilar languages under data imbalance. The approach significantly improves quality on English-to-Many, Many-to-English, and zero-shot translation tasks. The approach improves model generalization to out-of-distribution multilingual examples, and they analyze advantages at the representation level.


## Target Task

nlp

## Content

<Abstract: Multilingual neural machine translation models are trained to maximize the likelihood of a mix of examples drawn from multiple language pairs. In this paper, the authors introduce multilingual crossover encoder-decoder (mXEncDec) to fuse language pairs at an instance level. Their approach interpolates instances from different language pairs into joint ‘crossover examples’ in order to encourage sharing input and output spaces across languages. They propose several techniques to improve example interpolation across dissimilar languages under heavy data imbalance. Experiments on a large-scale WMT multilingual dataset demonstrate that their approach significantly improves quality on English-to-Many, Many-to-English and zero-shot translation tasks (from +0:5 BLEU up to +5:5BLEU points). Results on code-switching sets demonstrate the capability of their approach to improve model generalization to out-of-distribution multilingual examples. They also conduct qualitative and quantitative representation comparisons to analyze the advantages of their approach at the representation level.>



---

