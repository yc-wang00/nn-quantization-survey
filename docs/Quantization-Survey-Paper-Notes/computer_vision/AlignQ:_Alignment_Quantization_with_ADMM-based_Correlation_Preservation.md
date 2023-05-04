# AlignQ: Alignment Quantization with ADMM-based Correlation Preservation

## Summary

Summary: The paper proposes a new quantization method called AlignQ, which minimizes the quantization error caused by distribution differences between training and testing data using the cumulative distribution function. The method uses ADMM optimization to minimize differences in data correlations before and after quantization to retain prediction information. Experimental results show that the AlignQ method performs better, particularly in low-bit models. Code is available on GitHub.


## Target Task

computer vision

## Content

<Abstract:> 
We propose a new quantization scheme called Alignment Quantization with ADMM-based Correlation Preservation (AlignQ), which aims to minimize the quantization error induced by distribution differences between training and testing data. AlignQ exploits the cumulative distribution function (CDF) to align the data to be independently and identically distributed (i.i.d.) for quantization error minimization. Then, we leverage the Alternating Direction Method of Multipliers (ADMM) optimization to minimize the differences in data correlations before and after the alignment and quantization. Our theoretical analysis indicates that the significant changes in data correlations after the quantization induces a large quantization error; accordingly, we aim to preserve the relationship of data from the original space to the aligned quantization space for retaining the prediction information. Experimental results demonstrated that AlignQ achieves significant performance improvements, especially in low-bit models. Code is available at https://github.com/tinganchen/AlignQ.git.



---

