# LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale

## Info: 
- ___Date Submitted___:  15 Aug 2022
- ___Topic___: #transformer #efficient-ml #LLM 
- ___PDFLink___: [[PaperReview-LLM.int8()]]
- ___CodeLink___: integrated with Huggingface Accelerate library 

## Summary:  

LLM.int8() is a procedure for 8-bit matrix multiplication for transformers at scale. It reduces the memory needed for inference by half while maintaining full precision performance. LLM.int8() has a two-part quantization procedure, vector-wise quantization with separate normalization constants and a mixed-precision decomposition scheme. Using this, it is possible to perform inference in LLMs with up to 175B parameters without any performance degradation, making such models much more accessible. 

## Result/Achievement:

### Quantization Procedure
![[Pasted image 20230221111513.png]]

Language modeling perplexity results on the 125M to 13B Int8 models evaluated on the C4 corpus. The results in Table 1 show that absmax, row-wise, and zeropoint quantization fail as we scale, with models after 2.7B parameters performing worse than smaller models. Zeropoint quantization fails beyond 6.7B parameters. However, LLM.int8() is the only method that preserves perplexity, having a favorable scaling trend. Thus, LLM.int8() is the best method for scaling up language modeling.

![[Pasted image 20230221115440.png]]

LLM.int8() run times is about two times faster for large matrix multiplications equivalent to those in 175B models.

![[Pasted image 20230221115158.png]]

## Interesting ideas/Takeaway: 



## Personal Note: 


 